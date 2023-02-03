# b4rpipe-env
Python environment for the pipeline reduction by b4rpipe

## Basic usage

### Step 1: Install [Poetry](https://python-poetry.org)

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
