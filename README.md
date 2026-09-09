# REMM Result Review

This repository contains a static REMM result review map in `docs/` and the notebook used to generate review assets.

## Create the Python Environment

Install `uv`, then run from the repository root:

```powershell
uv sync
```

Start Jupyter with:

```powershell
uv run jupyter lab
```

Open `review_combined.ipynb` from Jupyter.

## Preview the Review Map Locally

Run from the repository root:

```powershell
uv run python -m http.server 8000
```

Then open:

```text
http://localhost:8000/docs/
```

## GitHub Pages

The public review map is served from the `docs/` folder. In GitHub Pages settings, use:

```text
Source: Deploy from a branch
Branch: main
Folder: /docs
```
