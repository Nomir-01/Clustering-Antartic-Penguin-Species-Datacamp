# Clustering Antarctic Penguin Species

An unsupervised machine-learning analysis that groups Antarctic penguins from their measured characteristics. The notebook standardizes the numeric features, evaluates possible cluster counts, and applies K-means clustering to produce an interpretable grouped dataset.

## Workflow

1. Inspect and prepare the penguin measurements.
2. Standardize features so measurements with different scales are comparable.
3. Evaluate candidate values for the number of clusters.
4. Fit a K-means model and attach cluster labels to the data.
5. Review the resulting cluster profiles.

## Tools

- Python and pandas
- scikit-learn (`StandardScaler` and `KMeans`)
- Matplotlib
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — exploratory analysis and clustering workflow
- `penguins.csv` — penguin measurements used in the analysis
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

The notebook is the primary project artifact and includes the executed analysis and outputs.

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates preprocessing for unsupervised learning, cluster selection, and interpretation of K-means results.
