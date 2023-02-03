# b4rpipe-env
Python environment for the pipeline reduction by [b4rpipe]

## Basic usage

### Step 1: Install [Poetry]

```shell
curl -sSL https://install.python-poetry.org | python3 -
```

### Step 2: Clone the repository

```shell
git clone https://github.com/b4r-dev/b4rpipe-env.git
```

### Step 3: Setup the Python environment

```shell
cd b4rpipe-env
poetry install
```

### Step 4: Run Python within the environment

Launch an interactive Python:

```shell
poetry run ipython
```

or run a Python script:

```shell
poetry run python /path/to/script
```

## Known issues

### Installation fails due to [sklearn]

[sklearn] is a dependency of [b4rpipe], however, it sometimes raises an installation error by itself to encourage migration to [scikit-learn].
If the installation fails, please retry at times other than those listed in the table below.

Dates | Times when an installation fails
--- | ---
2023 February 1st - March 31st | :00-:10 every hour
2023 April 1st - May 31st | :00-:15 every hour
2023 June 1st - July 31st | :00-:10 and :30-:40 every hour
2023 August 1st - September 30th | :00-:15 and :30-45 every hour
2023 October 1st - November 30th | :00-:20 and :00-50 every hour
2023 December 1st onwards | always raise an exception

[b4rpipe]: https://pypi.org/project/b4rpipe
[Poetry]: https://python-poetry.org
[sklearn]: https://pypi.org/project/sklearn
[scikit-learn]: https://pypi.org/project/scikit-learn

