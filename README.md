# 🛍️ Amazon Sales Analysis

This project explores product pricing, ratings, discount patterns, and category trends in Amazon product data.  
The goal is to uncover insights about **customer preferences**, **market trends**, and **pricing strategies**.

---

## 📂 Project Structure

Amazon_Sales_Analysis/
│
├── Amazon_sales_analysis.ipynb # Main analysis notebook
├── data/ # Dataset(s)
└── README.md # Project overview (this file)


---

## 🎯 Project Objectives

- Clean and preprocess messy product data
- Analyze rating and discount relationships
- Identify top-performing product categories
- Visualize pricing and rating trends
- Generate actionable business insights

---

## 🧹 Data Cleaning Steps

- Removed currency symbols and formatting issues
- Converted text values to numeric where needed
- Filled missing values appropriately
- Calculated a new `encoded_user_id` column with Label_Encoding


---

## 📊 Key Visualizations

| Visualization | Purpose |
|--------------|---------|
| Category distribution | Identify top-selling product categories |
| Rating vs Discount scatter plot | Check whether high discounts influence ratings |
| Correlation heatmap | Understand numeric feature relationships |

---

## 🔍 Insights

- **Electronics** and its related subcategories dominate the marketplace.
- Certain accessory categories like **USB Cables** show strong listing volume.
- **Rating and discount** do *not* strongly influence each other — implying customers value more than just offers.
- Popular items like **Smartwatches**, **Smartphones**, and **Mixer Grinders** continue to show strong performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

```bash
git clone <repo-url>
cd Amazon_Sales_Analysis
jupyter lab
```

---

🤝 Contribution

Feel free to fork and improve the analysis — PRs are welcome!

📜 License

This project is open-source under the MIT License.


