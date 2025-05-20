# 🛰️ SONAR Rock vs Mine Classification (Logistic Regression)

This project applies **Logistic Regression** to classify whether an object is a **Rock** or a **Mine** based on sonar signal data. The dataset is sourced from the **UCI Machine Learning Repository**.

**More the data,**
**More the accurate the model is**

---

## 📊 Dataset

- **Source**: [SONAR Dataset]([https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)](https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/view))
- **Rows**: 208
- **Features**: 60 numerical attributes (sonar signals)
- **Target**: 
  - `R` = Rock
  - `M` = Mine

---

## 🔍 Project Overview

- **Notebook**: `sonar_logistic_regression.ipynb`
- **Goal**: Binary classification (Rock vs Mine)
- **Model**: Logistic Regression
- **Tools Used**:
  - Python
  - Pandas
  - NumPy
  - Scikit-learn

---

## 📌 Steps Covered in the Notebook

1. **Load and explore the dataset**
2. **EDA** (heatmaps, class balance, etc.)
3. **Preprocessing** (label encoding: R → 0, M → 1)
4. **Split into train/test sets**
5. **Train logistic regression model**
6. **Evaluate**: accuracy, classification report

---

## 🚀 How to Run

1. Clone this repository or download the files.
2. Open the notebook in Jupyter or VS Code.
3. Ensure `sonar.csv` is in the same directory.
4. Run all cells to train and evaluate the model.

---

## 💡 Example Output

- Accuracy: ~75% (varies slightly depending on split)
- Model shows good distinction between Rocks and Mines

---

## ✅ Requirements

You can install required packages using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
