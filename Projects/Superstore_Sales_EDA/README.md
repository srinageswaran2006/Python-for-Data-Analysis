# 📊 Superstore Sales EDA

A simple exploratory data analysis project using the **Superstore retail dataset**.

The goal of this project was to practice **Pandas, Matplotlib, and Seaborn** while answering basic business questions related to **sales, profit, categories, regions, and customer segments**.

---

## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 📌 What I Analyzed

* Monthly sales trend
* Sales and profit comparison
* Sales by category and sub-category
* Regional sales performance
* Customer segment distribution
* Sales distribution
* Profit distribution by category
* Sales vs Profit relationship
* Correlation between key numerical features

---

## 📷 Key Visualizations

### Sales Distribution

![Sales Distribution](images/sales_distribution.png)

### Profit Distribution by Category

![Profit Distribution](images/profit_boxplot.png)

### Sales vs Profit Relationship

![Sales vs Profit](images/sales_profit_regression.png)

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📌 Key Findings

* The **sales distribution is highly right-skewed**, with the majority of orders concentrated below **$500**, while a small number of high-value transactions create a long tail extending beyond **$20,000**.

* **Technology** shows the **highest median profit** among all categories, indicating that it consistently generates stronger profits than Furniture and Office Supplies.

* **Office Supplies** has the **narrowest interquartile range (IQR)** and shorter whiskers, suggesting that its profits are **more stable and less volatile** compared with the other categories.

* **Furniture** contains several **negative-profit outliers**, showing that although many orders are profitable, a noticeable number of transactions result in substantial losses.

* The **Technology** category also exhibits the **widest spread of profit values**, with both very high profits and significant losses, making it the category with the **highest profit variability**.

* The **Sales vs Profit** analysis reveals a **moderate positive relationship** (**correlation ≈ 0.48**), meaning that higher sales generally tend to increase profit, but the relationship is not strong enough to guarantee profitability.

* Several **high-sales orders still produce negative profits**, indicating that **large revenue does not always translate into positive business performance**.

* The **Discount vs Profit** relationship shows a **negative correlation** (**≈ -0.22**), suggesting that increasing discounts tends to reduce profitability and may contribute to loss-making orders.

* **Quantity** has only a **weak positive relationship with sales** (**≈ 0.20**) and an almost negligible relationship with **profit** (**≈ 0.07**), implying that simply selling more units does not significantly improve profitability.

* Overall, the business appears to be **revenue-driven**, with **Technology acting as the primary profit engine**, while **Furniture requires closer pricing and discount control to reduce losses and improve margins**.

---

## 📁 Files

* `Superstore_EDA.ipynb` — complete analysis notebook
* `images/` — saved charts used in this README

This project is part of my **Python for Data Analysis** learning journey.
