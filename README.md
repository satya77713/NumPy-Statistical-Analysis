# NumPy Statistical Analysis

## 📌 Overview

This project demonstrates statistical analysis using Python and NumPy on a sales dataset. It focuses on calculating important statistical measures, analyzing sales patterns, and identifying potential outliers.

This project was completed as **Task 15** of the AI & ML Internship at **Veda Technology** using Google Colab.

## 🎯 Objective

To practice applying NumPy statistical functions to numerical data and identify meaningful patterns in a sales dataset.

## 🛠️ Tools and Technologies

- Python
- NumPy
- Pandas
- Google Colab

## 📂 Dataset

**Dataset filename:** `sales_data.csv`

The dataset contains sales records and numerical fields, including `Sales_Amount`, which is used for the statistical analysis.

The notebook loads the CSV file, selects the `Sales_Amount` column, converts its values to numeric format, and handles missing or invalid values before analysis.

## 📊 Tasks Performed

- Loaded the sales dataset using Pandas.
- Selected sales amounts for numerical analysis.
- Calculated mean and median.
- Calculated standard deviation.
- Identified minimum and maximum sales amounts.
- Compared mean and median to understand the distribution.
- Filtered low and high sales values.
- Identified potential outliers using the Interquartile Range (IQR) method.
- Recorded observations about the dataset.

## 🧮 Statistical Functions Used

| Function | Purpose |
|---|---|
| `np.mean()` | Calculates the average |
| `np.median()` | Finds the middle value |
| `np.std()` | Measures data variability |
| `np.min()` | Finds the minimum value |
| `np.max()` | Finds the maximum value |
| `np.percentile()` | Calculates percentiles for IQR analysis |

## 🔍 Outlier Detection

The project uses the Interquartile Range method to identify potential outliers.

- **Q1:** 25th percentile
- **Q3:** 75th percentile
- **IQR:** Q3 − Q1
- **Lower bound:** Q1 − 1.5 × IQR
- **Upper bound:** Q3 + 1.5 × IQR

Values outside these bounds are flagged as potential outliers for further investigation.

## 📈 Key Observations

The analysis of the provided dataset produced the following results:

- **Number of valid records:** 1,000
- **Mean sales amount:** 5,019.27
- **Median sales amount:** 5,019.30
- **Minimum sales amount:** 100.12
- **Maximum sales amount:** 9,989.04
- **Standard deviation:** 2,845.37

The mean and median are very close, while the minimum and maximum values show a wide range of sales amounts.

The IQR method did not identify any potential outliers in the dataset.

## ▶️ How to Run the Project

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Upload `sales_data.csv` when prompted by the notebook.
4. Copy the Task 15 Python code into a code cell.
5. Run the cell to calculate statistics and display observations.
6. Save the notebook as `NumPy_Statistical_Analysis.ipynb`.

## 📚 Learning Outcomes

- Learned how to apply NumPy statistical functions.
- Understood the difference between mean and median.
- Practiced interpreting standard deviation.
- Learned to identify minimum and maximum values.
- Used Boolean indexing to filter numerical data.
- Practiced identifying potential outliers using the IQR method.
- Improved practical data analysis skills using Python.

## 🏁 Conclusion

This project provided hands-on experience with statistical analysis using NumPy. It demonstrated how statistical measures can help summarize sales data, understand variability, and investigate unusual values.

These skills form a useful foundation for data analysis and machine learning.

## 👨‍💻 Internship Details

- **Organization:** Veda Technology
- **Track:** AI & ML
- **Task:** 15 — NumPy Statistical Analysis
- **Platform:** Google Colab
