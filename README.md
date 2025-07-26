# Capstone Project — Predicting Purdue’s NCAA Tournament Performance

A data‑science capstone from my final semester at Purdue University.  
We built several classification models (Logistic Regression, SVM, KNN, Random Forest) to predict how many games Purdue would win in the 2024 NCAA Tournament, and evaluated them against both business and data‑science success criteria.

---

## 📁 Project Structure

```text
marchmadness-prediction/
├── README.md
├── .gitignore
│
├── data/
│   ├── final_predictions.csv    # Model outputs on hold‑out set
│   ├── training_data.csv        # Data used to train models
│   ├── val_data.csv             # Validation split
│   └── misc_data*/               # All other raw/source datasets
│       └── ...
│
├── notebooks/
│   ├── 01_preprocessing1.ipynb
│   ├── 02_preprocessing2.ipynb
│   ├── 03_preprocessing3.ipynb
│   ├── 04_preprocessing4.ipynb
│   ├── 05_understanding1.ipynb
│   ├── 06_understanding2.ipynb
│   └── 07_modeling.ipynb
│
├── reports/
│   ├── evaluation_report.pdf    # Evaluation metrics & error analysis
│   └── modeling_report.pdf      # Modeling approach & results
│
└── slides/
    ├── 01_project_understanding.pdf
    ├── 02_data_prep.pdf
    ├── 03_modeling.pdf
    └── 04_conclusion.pdf
```
---

## 🚀 Getting Started

> No installation or live execution required—this is a static snapshot of the analysis.

1. **Browse Notebooks on GitHub**  
   - GitHub will render each notebook with its saved outputs.  

2. **View Reports & Slides**  
   - PDFs in `reports/` and `slides/` can be previewed directly in‑browser.  

3. **(Optional) Explore the Data**  
   - Download any of the `.csv` files under `data/` for your own inspection or analysis.

---

## 🔖 License

This work is released under the [MIT License](LICENSE).

---

## 📝 Acknowledgments

- Team: Saul Means, Kuba Bal, Sarah Firestone, Zachary Hanson, Avi Khurana  
- Data sources: KenPom, Kaggle NCAA datasets, Vegas odds feeds  

---

*(Note: “misc_data/” contains auxiliary datasets that were part of our feature‑engineering pipeline.)*  
