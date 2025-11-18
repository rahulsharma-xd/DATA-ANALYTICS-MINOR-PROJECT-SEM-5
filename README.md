
# Fintech Transactions Dataset – Cleaned Version

This dataset contains cleaned and standardized fintech transaction records for analysis or use in machine learning pipelines.

## 🧹 Cleaning Process

The original dataset contained inconsistencies in formatting and missing values. Below steps were taken to clean and normalize the dataset:

### 1. **Date Formatting**
- All dates were converted to a unified format: `YYYY-MM-DD`
- Various formats like `"18/05/2024"`, `"Jun 15, 2024"`, and `"2023-09-25"` were parsed and standardized

### 2. **Amount Cleaning**
- Removed currency symbols (`$`, `€`) and unwanted text (e.g., `"USD"`)
- Only numeric values retained
- Converted to `float` for numerical use

### 3. **Standardized Fields**
- `Merchant`, `Category`, `Payment_Method`, and `Status` were formatted in a consistent Title Case or UPPERCASE
- Country names corrected:
  - `"Uk"` → `"United Kingdom"`
  - `"Usa"` → `"United States"`

### 4. **Handling Missing Data**
- Rows with any missing (`NaN`) values were removed
- Final dataset contains only fully populated rows

## 📁 Files Included

| Filename                                      | Description                                 |
|-----------------------------------------------|---------------------------------------------|
| `fintech_transactions_cleaned.csv`            | Cleaned data with standard formatting        |
| `fintech_transactions_cleaned_no_null.csv`    | Cleaned data with **no missing values**      |

## 🔍 Suggested Use Cases

- Transactional fraud detection
- Personal finance visualizations
- Customer behavior analysis
- Machine learning model training or data wrangling exercises

## ⚠️ Notes

- This dataset is anonymized and for research use only.
- If you’re using this for financial modeling, ensure amounts are converted to a single currency.
