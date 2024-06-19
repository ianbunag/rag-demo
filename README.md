# Retrieval Augmented Generation

## Quick start

### Create virtual environment

```sh
python3 -m venv .venv
```

### Activate virtual environment

```sh
source .venv/bin/activate
```

### Install dependencies

```sh
pip install -r requirements.txt
python -m ipykernel install --user --name .venv
```

### Run notebook

```sh
jupyter notebook
```

## Generating dependency lockfile

```sh
pip freeze > requirements.txt
```

## References

- https://python.langchain.com/v0.2/docs/tutorials/rag/
- https://jupyter.org/install#jupyter-notebook
- https://stackoverflow.com/a/33468993
