# 🧹 Data Preprocessing - Sales Dataset

This repository contains a Jupyter Notebook that performs full **data cleaning and preprocessing** on a synthetic sales dataset containing 5000 rows. It includes handling of missing values, duplicates, type conversion, encoding, and basic feature engineering — everything you need to prepare your data for EDA or modeling.

---

## 📁 Files

- `sales_data.csv` - Raw sales dataset with missing values and duplicates.
- `Data_Cleaning_Preprocessing_Sales.ipynb` - Jupyter notebook containing the complete data cleaning pipeline.
- `data_cleaning_and_preprocessing.pdf` - A well-documented PDF summary of all the steps performed.

---

## 🧰 Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 Steps Covered in Preprocessing

1. **Import Required Libraries**
2. **Load and Inspect Dataset**
3. **Handle Missing Values**
   - Fill categorical with `'Unknown'`
   - Fill numeric with median or zero
4. **Remove Duplicates**
5. **Convert Data Types**
   - Parse dates
   - Convert categoricals
6. **Validate Data**
   - Ensure no negative or invalid values
7. **Encode Categorical Features**
   - One-hot encoding for machine learning
8. **Feature Engineering**
   - Extract year, month, and weekday from `Order Date`
9. **Final Checks**

---

## 📝 How to Use

1. Clone this repository or download the notebook.
2. Open `Data_Cleaning_Preprocessing_Sales.ipynb` in Jupyter.
3. Run cells step-by-step or modify to fit your data.
4. Use the cleaned dataset for EDA or modeling.

---

## 📌 Example Output

| Feature       | Cleaned Type | Description                  |
|---------------|---------------|------------------------------|
| Sales         | float          | Missing values filled (median) |
| Customer Name | string         | Missing values filled ('Unknown') |
| Order Date    | datetime       | Parsed to datetime            |
| Region        | category       | Encoded for ML                |

---

## 📬 Contact

For questions, feel free to reach out or open an issue.

---

**⭐️ Star this repo if you find it helpful!**
