# International Trade Data Analysis & Pipeline

## Project Overview
This repository contains the assignment: **International Trade Data Analysis & Pipeline**.  
It includes data processing scripts, SQL examples, a Jupyter notebook, documentation, and the final PDF report.

## Folder structure
- `src/` - Main Python scripts and modules.
- `data/` - Sample input datasets (CSV) or placeholders.
- `notebooks/` - Jupyter notebooks for exploratory analysis and visualizations.
- `sql/` - SQL scripts and schema examples.
- `docs/` - Additional documentation and the final PDF report.
- `.github/` - GitHub actions or templates (if needed).

## Quickstart (local)
1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate    # on Windows: venv\Scripts\activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main pipeline:
   ```bash
   python src/main.py --input data/trade_sample.csv --output docs/report_summary.csv
   ```

## Contents
- `docs/assignment.pdf` — Final assignment report (PDF).
- `src/main.py` — Example ETL pipeline to load, transform, and summarize trade data.
- `notebooks/analysis.ipynb` — Notebook placeholder for EDA and charts.
- `sql/schema.sql` — Example schema for storing trade data.

## License
This project is released under the MIT License. See `LICENSE` for details.
