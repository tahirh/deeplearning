# deep-learning

## Setup

Install dependencies with [uv](https://docs.astral.sh/uv/):

```bash
uv sync
```

## Running the script

```bash
uv run main.py
```

## Running Jupyter notebooks

Jupyter is included as a dev dependency. Launch Jupyter Lab from the project root with:

```bash
uv run jupyter lab
```

Or, for the classic notebook interface:

```bash
uv run jupyter notebook
```

This opens Jupyter in your browser with access to the project's virtual environment, so any installed dependencies (e.g. `keras`) are available in the notebook. A starter notebook is at `notebooks/example.ipynb`.
