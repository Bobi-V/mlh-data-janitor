## MLH Data Janitor Task

Python implementation of [dataset cleaning task](https://www.mlh.com/challenges/019abf91-3148-c994-f4d8-53dcef17288f).

### Local install

If you want to run the project you can use the [`uv`](https://docs.astral.sh/uv/getting-started/installation/) multi purpose package manager to get set up quickly with the following commands

```
uv venv <name of your .venv file>
uv sync
source <name of your .venv file>/bin/activate
```

To install the dataset make sure you are authenticated with Kaggle by making a `.env` file in the root of the project with the following variables

```
KAGGLE_API_TOKEN=YOUR_KAGGLE_API_TOKEN 
```
