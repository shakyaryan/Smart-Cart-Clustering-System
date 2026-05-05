# 🛒 SmartCart Customer Data Analysis

## 📌 Project Overview

SmartCart Customer Data Analysis is a data analytics project focused on understanding customer demographics, behavior, and spending patterns. The goal is to transform raw customer data into meaningful insights that can support data-driven business decisions.

---

## 📂 Dataset

The dataset (`smartcart_customers.csv`) contains customer information such as:

* Demographics (age, income, education, marital status)
* Purchase behavior across product categories
* Household composition (kids, teens)
* Customer enrollment date

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib
* Seaborn

---

## 🧹 Data Preprocessing

Key preprocessing steps performed:

* Handling missing values (Income filled with median)
* Converting date columns to proper datetime format
* Removing irrelevant or redundant columns
* Cleaning categorical variables (Education, Marital Status)

---

## 🛠️ Feature Engineering

New features were created to enrich analysis:

* **Age** → Derived from birth year
* **Customer Tenure** → Days since customer enrollment
* **Total Spending** → Sum of all product category purchases
* **Total Children** → Combined count of kids and teens
* **Living Status** → Simplified marital categories
* **Education Level** → Grouped into broader categories

---

## 📊 Exploratory Data Analysis (EDA)

The project uses visualization techniques to:

* Understand customer income distribution
* Analyze spending patterns
* Identify relationships between demographics and purchases
* Explore customer segmentation opportunities

---

## 📁 Project Structure

```
├── smartcart(1).ipynb       # Main analysis notebook
├── smartcart_customers.csv  # Dataset
└── README.md                # Project documentation
```

---

## 🚀 How to Run the Project

1. Clone the repository or download the files
2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Run `smartcart(1).ipynb`

---

## 📈 Key Insights

* Customers’ spending behavior varies significantly by income and family size
* Feature engineering improves interpretability of raw data
* Customer tenure can help identify loyal vs new customers

---

## 🎯 Future Improvements

* Apply machine learning for customer segmentation (e.g., clustering)
* Build predictive models for customer spending
* Deploy a dashboard for interactive insights

---

## 🤝 Contributing

Feel free to fork this repository and improve the analysis or add new features.

---

## 📜 License

This project is open-source and available under the MIT License.