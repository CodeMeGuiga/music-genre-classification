# Music Genre Classification

Builds a machine learning pipeline to classify music samples into genres (Blues, Classical, Country, Disco, HipHop, Jazz, Metal, Pop, Reggae, Rock) from audio features, working with a deliberately messy dataset (missing labels, noisy/corrupt entries).

## Contents

- `notebook.ipynb`: data cleaning, feature extraction (via `librosa`), model training and evaluation.
- `report.pdf`: write-up of the approach and results.

## Running it

```bash
pip install librosa pandas numpy scikit-learn datasets
jupyter notebook notebook.ipynb
```
