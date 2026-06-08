# Machine Learning

A structured collection of Jupyter notebooks, datasets, and reference materials covering the full Machine Learning pipeline — from data wrangling to deep learning — developed as part of a university-level ML course.

---

## Contents

### Core Modules

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | [Introduction](1-Introducción/) | Python fundamentals, ML overview, course foundations |
| 2 | [Data Types](2-Tipos%20de%20Datos/) | Structured vs. unstructured data, Titanic dataset |
| 3 | [Data Cleaning](3-Limpieza%20de%20Datos/) | Handling missing values, outliers, IMDb & video game datasets |
| 4 | [Data Analysis](4-Análisis%20de%20Datos/) | EDA, pivot tables, joins, COVID & Buenos Aires open data |
| 5 | [Linear Regression](5-Regresión%20Lineal/) | OLS, multidimensional regression, Boston Housing, SGD |
| 6 | [Polynomial Regression](6-Regresión%20Polinómica/) | Non-linear fitting, overfitting, regularization |
| 7 | [Logistic Function](7-Función%20Logística/) | Sigmoid, binary classification setup |
| 8 | [Applied Logistic Regression](8-Regresión%20Logística%20Aplicada/) | Classification pipeline on real-world data |
| 9 | [Gradient Descent](9-Gradiente%20Descendente/) | Manual GD implementation, convergence analysis |
| 10 | [SVM & Naive Bayes](10-SVM%20y%20Naive%20Bayes/) | Linear/kernel SVMs, probabilistic classification, Titanic |
| 11 | [Segmentation](11-Segmentación/) | K-Means clustering, KNN, Decision Trees, class imbalance |
| 12 | [Deep Learning](12-Deep%20Learning/) | Perceptron, neural network architectures |
| 13 | [Entropy & Information Theory](13.Entropy/) | Shannon entropy, information gain, decision boundaries |

### Homeworks & Applied Projects

| Project | Description |
|---------|-------------|
| [Air Quality in Castilla](Homeworks/Air%20Quality%20in%20Castilla/) | Regression on environmental sensor data |
| [Bogota Schools](Homeworks/Bogota%20Schools/) | EDA and classification on public education data |
| [Cigarettes](Homeworks/Cigarrettes/) | Data cleaning and feature engineering |
| [Ensemble Algorithms](Homeworks/Ensemble%20Algorithms/) | Bagging, boosting, and model stacking |
| [Logistic Classification](Homeworks/Logistic%20Classification/) | Binary classification on the Affairs dataset |
| [Photoelectric Effect](Homeworks/Fotoelectric/) | ML applied to physics experimental data |
| [Optics](Homeworks/Optics/) | Regression on optical measurements |
| [Oscillators](Homeworks/Osciladores/) | Time-series modeling of physical oscillations |
| [Pokemon Scraper](Homeworks/Pok%C3%A9mon/) | Web scraping pipeline with BeautifulSoup |
| [Protein Structure](Homeworks/Protein/) | Classification on PDB structural data |
| [Stars](Homeworks/Stars/) | Stellar classification from spectral features |
| [Zeeman Effect](Homeworks/Zeeman/) | Curve fitting on atomic spectra measurements |
| [KNIME Workflows](Homeworks/KNIME/) | Visual ML pipelines with KNIME |
| [TANAGRA](Homeworks/TANAGRA/) | Data mining with the TANAGRA platform |
| [Web Scraper](Homeworks/Web%20Scraper/) | Real estate scraping from MercadoLibre Colombia |

---

## Tech Stack

- **Language:** Python 3
- **Core libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Deep learning:** PyTorch
- **Environment:** Jupyter Lab / Jupyter Notebook
- **Other tools:** KNIME, TANAGRA

---

## Structure

```
MACHINE-LEARNING/
├── 1-Introducción/          # Python basics + ML foundations PDFs
├── 2-Tipos de Datos/
├── 3-Limpieza de Datos/
├── 4-Análisis de Datos/
├── 5-Regresión Lineal/
├── 6-Regresión Polinómica/
├── 7-Función Logística/
├── 8-Regresión Logística Aplicada/
├── 9-Gradiente Descendente/
├── 10-SVM y Naive Bayes/
├── 11-Segmentación/
├── 12-Deep Learning/
├── 13-Entropy/
└── Homeworks/               # Applied projects across diverse domains
```

---

## Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/<your-username>/MACHINE-LEARNING.git
cd MACHINE-LEARNING
```

**2. Create a virtual environment and install dependencies**
```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install numpy pandas matplotlib seaborn scikit-learn torch jupyterlab
```

**3. Launch Jupyter**
```bash
jupyter lab
```

Open any `.ipynb` notebook to explore a topic or project.

---

## License

This repository is for educational purposes. Datasets are sourced from public domain and open data initiatives.
