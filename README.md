# zoomcamp-ml-course

## Jupyter

```sh
uvx jupyter lab
```

Add 8888 

## Activation of environment

```sh
source .venv/bin/activate
```

## Assign env from uv to notebook

```sh
uv add pandas jupyter ipykernel
uv run python -m ipykernel install --user --name=zoomcamp --display-name "Python (zoomcamp)"
```