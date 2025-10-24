# Marketing Analytics & Data Science Portfolio

A curated portfolio of marketing analytics and health data science projects.  
Core topics include CLV/RFM, logistic regression, lift & gain curves, decision trees/forests, neural networks, recommender systems, sentiment analysis, and LLM applications for marketing.  
All notebooks are designed to run on **Google Colab** or locally with Python 3.10+.

## What’s inside
- **notebooks/**: Clean, reproducible Colab/ Jupyter notebooks from classroom labs and personal extensions.
- **src/**: Reusable utilities (data wrangling, metrics, plots, models).
- **projects/**:
  - **birth-outcomes-hispanic-us/** — population-scale analysis (9M+ births), logistic models + interpretable trees, subgroup fairness.
  - **marketing-capstone/** — applied, end-to-end project (problem framing → modeling → business recommendation).
- **assignments/**: Six modular mini-projects with instructions.
- **exams/**: Review notes and practice material.
- **syllabus/**: Course info I’m permitted to share.

## Quick start
**Option A: Colab (zero setup)**
1. Open any notebook in `notebooks/`.
2. Click: *Open in Colab* → run cells (first cell installs lightweight deps).

**Option B: Local (Python 3.10+)**
```bash
python -m venv .venv && source .venv/bin/activate   # or .venv\Scripts\activate on Windows
python -m pip install -U pip
pip install -r requirements.txt
jupyter lab
