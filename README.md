# 🧬 SLE-Insights

**An Explainable AI Companion for Transcriptomic Biomarker Discovery in Systemic Lupus Erythematosus**

SLE-Insights is an interactive web application developed to accompany our research on transcriptomic biomarker discovery for **Systemic Lupus Erythematosus (SLE)**. The platform integrates explainable artificial intelligence (XAI), machine learning, and biological pathway analyses into an intuitive interface for exploring diagnostic biomarkers, disease activity markers, and model performance.

Built using **Streamlit**, SLE-Insights enables researchers, clinicians, and students to interactively explore the complete analytical workflow, biological interpretations, and validation results presented in the accompanying research study.

---

## 📖 Overview

Systemic Lupus Erythematosus (SLE) is a heterogeneous autoimmune disease characterized by complex molecular mechanisms and highly variable clinical manifestations. Reliable molecular biomarkers are essential for improving early diagnosis and disease monitoring.

This project combines transcriptomic data analysis with explainable machine learning to identify robust biomarkers and develop an interpretable diagnostic framework.

The study incorporates:

- Transcriptomic biomarker discovery
- SHAP-based explainable AI
- Machine learning classification
- Disease activity prediction
- Functional enrichment analysis
- Protein-protein interaction analysis
- Independent external validation

---

## ✨ Features

### 🧬 Biomarker Explorer

- Interactive exploration of all identified biomarkers
- Biological function and clinical significance
- Gene-specific literature summaries
- STRING protein interaction networks
- KEGG pathway enrichment
- Enrichr functional enrichment
- Study evidence for each biomarker

---

### 🤖 Model Development

- Complete machine learning workflow
- SHAP-based feature selection
- Model comparison
- Hyperparameter optimization
- Logistic Regression model development
- Cross-validation strategy

---

### 🩺 Diagnostic Prediction

- Eight-gene diagnostic signature
- Final model performance
- Clinical interpretation
- Decision threshold analysis

---

### 📈 Disease Activity Analysis

- Top severity-associated biomarkers
- Disease activity model evaluation
- Comparative ROC analysis
- Biological interpretation

---

### 📊 Results & Figures

Interactive visualization of:

- ROC Curves
- Confusion Matrices
- Calibration Curves
- External Validation
- SHAP Explainability
- Biological Validation
- Supplementary Figures

---

## 🧪 Datasets

| Dataset | Purpose |
|----------|---------|
| GSE65391 | Diagnostic biomarker discovery |
| GSE88884 | Disease activity analysis |
| GSE61635 | Independent external validation |

Data were obtained from the **NCBI Gene Expression Omnibus (GEO)**.

---

## 🧠 Machine Learning Pipeline

The analytical workflow consists of:

1. Transcriptomic data acquisition
2. Data preprocessing and normalization
3. Feature selection using SHAP
4. Machine learning model training
5. Cross-validation
6. Diagnostic prediction
7. Disease activity prediction
8. Functional enrichment analysis
9. External validation

---

## 📈 Key Results

### Diagnostic Model

- **Final Classifier:** Logistic Regression
- **Diagnostic Biomarkers:** 8 genes
- **Accuracy:** 95.5%
- **ROC-AUC:** 0.983
- **External Validation:** Successfully validated using GSE61635

### Disease Activity

- Top 20 severity-associated genes identified
- Best ROC-AUC: 0.706
- Demonstrated the complexity of disease activity prediction beyond transcriptomic biomarkers alone

### Overlapping Biomarkers

Three biomarkers were identified in both diagnostic and disease activity analyses:

- IFI27
- ZBP1
- CDCA7

---

## 🛠️ Technologies Used

### Programming

- Python

### Machine Learning

- Scikit-learn
- SHAP

### Bioinformatics

- GEOparse
- gseapy
- pandas
- NumPy

### Visualization

- Streamlit
- Plotly
- Matplotlib

---

## 📂 Project Structure

```text
SLE-Insights/

│── assets/
│── data/
│── models/
│── utils/
│── pages/
│── app.py
│── requirements.txt
│── README.md
```

---

## 🚀 Running the Application

Clone the repository

```bash
git clone https://github.com/yourusername/SLE-Insights.git
```

Navigate to the project

```bash
cd SLE-Insights
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch the application

```bash
streamlit run app.py
```

---

## 📚 Research Applications

This application can be used for:

- Biomarker exploration
- Explainable AI education
- Transcriptomic data interpretation
- Machine learning visualization
- Bioinformatics teaching
- Companion resource for the associated manuscript

---

## ⚠️ Disclaimer

This application is intended **solely for research and educational purposes**. The diagnostic models and biomarkers presented here have **not** been clinically validated for routine medical use and should not be used for clinical decision-making.

---

## 🙏 Acknowledgements

We acknowledge the investigators who generated and publicly shared the transcriptomic datasets through the **Gene Expression Omnibus (GEO)**.

We also thank the developers of the open-source libraries that made this work possible, including:

- Streamlit
- Scikit-learn
- SHAP
- GEOparse
- gseapy
- Plotly
- Matplotlib
- pandas
- NumPy

---

## 📄 Citation

If you use this repository in your research, please cite the accompanying manuscript once published.

---

## ⭐ Future Work

- Multi-omics integration
- Deep learning-based biomarker discovery
- Prospective clinical validation
- Drug target prioritization
- Explainable disease activity prediction
- Deployment with cloud-hosted inference

---

**SLE-Insights**  
*An Explainable AI Companion for Transcriptomic Biomarker Discovery in Systemic Lupus Erythematosus*
