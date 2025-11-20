# 📦 Olist E-Commerce Analysis (EDA + Power BI Dashboard)

This project explores the **Brazilian E-Commerce Public Dataset** by Olist, including a full **Exploratory Data Analysis (EDA)** in Python and a complete **interactive Power BI dashboard**.

The project is structured into two main components:

1. **EDA in Jupyter Notebook** — deep dive into customer behavior, delivery performance, seller patterns, review text analysis, and KPI creation.  
2. **Power BI Dashboard** — five pages (Overview, Customers, Sellers, Deliveries, Reviews) for interactive exploration of all insights.

---

## 📊 Interactive Dashboard (Power BI)

👉 **[Click here to explore the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjkwYjcxNjUtNWZmYS00MzBhLTlhMWQtNTFhN2YyY2Q0YTQxIiwidCI6ImEzNGM1MTliLTQ0ZDEtNGRlNi1iNTVlLWQ0NmNmZWFhODJhNSJ9)**  
*(opens in your browser — no download required)*

---

## 🖼️ Dashboard Preview

Below is a preview of the **Overview page** of the Power BI dashboard:

<p align="center">
  <img src="images/dashboard_overview.png" alt="Olist Dashboard Overview" width="800">
</p>

---

## 🗂️ Dashboard Files (Downloadable)

### **📁 Power BI (PBIX)**  
GitHub cannot preview PBIX files, but they can be downloaded:

- `Dashboard/olist_performance_dashboard.pbix`

### **📄 PDF Version (Static Pages)**

- `olist_performance_dashboard.pdf`

---

## 📘 Jupyter Notebook (EDA)

- `Notebooks/EcommercePerformanceEDA.ipynb` — full analysis including:
  - Data cleaning & preparation  
  - Revenue & demand trends  
  - Cohort analysis  
  - Delivery punctuality impact  
  - Review text mining (bigrams, trigrams, sentiment tendencies)  
  - Seller concentration metrics  
  - KPI definitions for BI consumption  

---

## 🔍 Key Insights

- **Delivery punctuality is the strongest driver of customer satisfaction**  
  - On-time delivery avg rating ≈ **4.21**  
  - Late delivery avg rating ≈ **2.55**

- **Sales are highly concentrated**  
  - Top 10% of sellers handle **~68% of all orders**

- **Text analysis shows the most common customer complaints relate to:**  
  - Product not arriving  
  - Delays  
  - Incorrect or missing items  

---

## 📁 Dataset

The dataset is not included in the repository.  
Download it from Kaggle:  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## ▶️ How to Run the Notebook

1. Clone repository:

```bash
git clone https://github.com/AlexPanoni/Olist_Ecommerce_Analysis.git
cd Olist_Ecommerce_Analysis
```

2. Create a Python environment:

```bash
python -m venv env

# Windows
env\Scripts\activate

# macOS / Linux
source env/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Place the CSV files into the `Datasets/` folder.

5. Launch the notebook:
```bash
jupyter notebook Notebooks/EcommercePerformanceEDA.ipynb
```

## ⭐ Project Structure

```
Olist_Ecommerce_EDA/
│
├── Dashboard/
│   ├── Olist_Dashboard.pbix
│   └── Olist_Dashboard.pdf
│
├── Images/
│   ├── dashboard_overview.png
│   ├── dashboard_customers.png
│   ├── dashboard_sellers.png
│   ├── dashboard_deliveries.png
│   └── dashboard_reviews.png
│
├── Notebooks/
│   └── EcommercePerformanceEDA.ipynb
│
├── README.md
└── requirements.txt
```



