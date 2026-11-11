# ML Midterm – Breast Cancer & Wine

**Muhammed Efe Öneş – 23040202015**

- **Repository:** https://github.com/muhammedefeones/ml-midterm-23040202015
- **Video:** https://youtu.be/OlxBqkiMlMQ

Classification (Decision Tree, KNN, Gaussian NB) and K-Means on two scikit-learn datasets: 132 classifier fits + 12 K-Means fits.

## Files

- `breast_cancer.ipynb`, `wine.ipynb` – notebooks (Sections 1–10 + export)
- `report.docx` – report
- `results/` – 6 CSV files
- `figures/` – 20 figures
- `requirements.txt` – package versions
- `AI_DISCLOSURE.md` – AI use

## Datasets

`load_breast_cancer` and `load_wine` from scikit-learn (originally from the UCI Machine Learning Repository). No download needed.

## How to run

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Open each notebook and run **Restart → Run All** (first `breast_cancer.ipynb`, then `wine.ipynb`).

## Versions

Python 3.13.16 · numpy 2.5.4 · pandas 3.1.1 · scikit-learn 1.9.1 · matplotlib 3.11.2 · seaborn 0.13.2
