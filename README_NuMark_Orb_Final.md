# 🧬 NuMark Orb – Real Data Cancer Risk Detection (Final Submission)

## 📘 Project Overview

**NuMark Orb** is an AI-powered cancer risk detection platform that uses RNA gene expression data, such as saliva samples, to predict cancer risk levels (low or high). It offers a patient-friendly and physician-integrated workflow for early detection and alerts.

---

## ⚙️ Installation Instructions

1. Open the final notebook using [Google Colab](https://colab.research.google.com/) or Jupyter.
2. Upload the notebook: `NuMark_Orb_Final_RealData_Notebook_With_OutputVisuals.ipynb`
3. Ensure the following files are also available:
   - ✅ `real_rna_data.csv` (used to train the model)
   - ✅ `sample_saliva_input.csv` (simulated test input)

---

## 🚀 Usage Guide (For Professors / Reviewers)

Please run the notebook **in order**, following these steps:

1. **Step 1:** Run the cell to upload your real training data CSV:
   - Upload `real_rna_data.csv` when prompted
2. **Step 2:** Run the training + evaluation cells to generate and save the model.
3. **Step 3:** When prompted to upload a new test sample, use `sample_saliva_input.csv`.
4. **Step 4:** Run the prediction and visualization cells:
   - This includes risk alerts, a summary table, and 3 visualizations:
     - 📊 Bar chart: Prediction count
     - 📈 Histogram: High-risk probabilities
     - 🔬 Feature importance chart (top gene markers)

This will demonstrate the **full end-to-end pipeline** in action with real data — no mock logic required.

---

## 🧠 AI Model Implementation

- **Model Type:** Random Forest Classifier (from `scikit-learn`)
- **Preprocessing:** StandardScaler (normalization of gene expression values)
- **Output:** Binary classification → `0 = Low Risk`, `1 = High Risk`
- **Visual Explanation:** Uses built-in feature importance plot (no SHAP issues)

---

## ⚖️ Ethical Considerations & Limitations

- NuMark Orb is not intended to replace clinical diagnosis.
- All predictions must be interpreted by licensed professionals.
- Data privacy and compliance with HIPAA/PHIPA is critical.
- Saliva and RNA test input must be processed from validated lab-grade devices.

---

## 📁 Included Files in This Repository

| File | Description |
|------|-------------|
| `NuMark_Orb_Final_RealData_Notebook_With_OutputVisuals.ipynb` | The main notebook |
| `real_rna_data.csv` | Example training data |
| `sample_saliva_input.csv` | Example saliva sample |
| `cancer_risk_rf_model.pkl` | Model saved during notebook run |
| `README.md` | This file with full instructions |

---

## 👥 Contributors – NuMark Orb Team

- Dharmesh Patel  
- Basim Awan  
- Hannah Keeler  
- Aravind Thiyagarajan  
- Adriana Cortés Soto  
- Emi Wayner

---

✅ This notebook can be opened and run entirely in Colab or Jupyter with just the above `.csv` files uploaded when prompted.