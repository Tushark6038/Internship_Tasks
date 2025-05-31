# TASK-1
# 🚢 Titanic Dataset - Cleaned Version by Me

This repository contains a cleaned version of the Titanic dataset from Kaggle, consolidated into a single Excel file. The goal of this project was to clean and prepare the data for use in machine learning models and data analysis.

----

## 📦 Dataset Files

- [`train.csv`](https://github.com/Tushark6038/Internship_Tasks/blob/89fe3df27e3a2918e52e03bd07e14011dabc8c75/train.csv) – Raw training data
- [`test.csv`](https://github.com/Tushark6038/Internship_Tasks/blob/5df4191a2a95375bcfd8a3d47a88b634ce431e30/test.csv) – Raw test data
- [`gender_submission.csv`](https://github.com/Tushark6038/Internship_Tasks/blob/4ebe6600899d518c1fd372562be294db6506a89c/gender_submission.csv) – Sample submission file
- [`cleaned_train.csv`](https://github.com/Tushark6038/Internship_Tasks/blob/28277a97127add5a169d79f00f90b2834a201cd9/Cleaned%20Dataset.csv) – ✅ Cleaned training dataset
  
This file includes:
- ✅ Preprocessed and cleaned **training and test data**
- 📊 Features ready for visualization and machine learning

---

## 🛠️ Key Cleaning Steps Performed

1. **Missing Values Handled**
   - `Age`, `Fare`, and `Embarked` were filled using median or mode
   - `Cabin` was dropped due to excessive missingness

2. **Categorical Encoding**
   - Converted `Sex` and `Embarked` into numeric labels using label encoding

3. **Irrelevant Columns Removed**
   - Removed `Ticket` and `Cabin` to reduce noise and complexity

4. **Exported Clean File**
   - All changes stored in `Cleaned Dataset.xlsx` for convenience

---

## 📊 Ready for ML!

You can now use `Cleaned Dataset.xlsx` for:
- ✅ Building classification models (e.g., survival prediction)
- ✅ Exploratory data analysis (EDA) and visualizations
- ✅ Kaggle submissions after appropriate splitting

---

## 📧 Contact

For any feedback or suggestions, feel free to reach out!

---

## 🔗 Link to Dataset

[👉 Download Cleaned Dataset.xlsx](https://github.com/Tushark6038/Internship_Tasks/blob/28277a97127add5a169d79f00f90b2834a201cd9/Cleaned%20Dataset.csv)

---

## 💻 Tools Used

- **Excel for final export**
