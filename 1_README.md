# Netflix Analysis

This repository contains a data analysis project focused on Netflix titles and credits. It includes raw CSV data, visualizations, and a Jupyter notebook that explores content distribution, ratings, runtime, genres, and other audience insights.

## Project structure

- `dashboard/` — dashboard-related files or visualization assets
- `data/` — source data files (`titles.csv`, `credits.csv`)
- `images/` — images used in reports or documentation
- `notebooks/` — Jupyter notebook(s) for analysis
- `requirements.txt` — Python dependencies for reproducing the environment
- `.gitignore` — standard ignores for Python and notebooks

## Setup

1. Create and activate a virtual environment:
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   - `notebooks/netflix_analysis.ipynb`

## Notes

- The notebook outputs have been cleared for a clean commit.
- The repository now ignores `.venv/`, `__pycache__/`, and notebook checkpoint files.
- If the dataset is large or private, consider excluding it from GitHub and adding a download instruction instead.

## Data files

- `data/titles.csv` — Netflix content metadata
- `data/credits.csv` — cast and crew metadata
