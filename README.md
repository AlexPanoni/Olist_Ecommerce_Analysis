# Olist E-Commerce Analysis (EDA)

**Overview**  
This project explores the Olist Brazilian E-Commerce dataset and contains a complete exploratory data analysis (EDA) implemented in a Jupyter notebook.

**Notebook**  
- `Notebooks/EcommercePerformanceEDA.ipynb` — main analysis.

**Key highlights**  
- Delivery punctuality strongly drives customer satisfaction (on-time avg ≈ 4.21 vs late ≈ 2.55).  
- Top 10% of sellers handle ~68% of orders (strong concentration).  
- Negative reviews frequently mention delivery issues (e.g., "didn't receive product").

**Data**  
The full CSV files from Kaggle are **not** included. Download link: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

**How to run**
1. Clone repo:
```bash
git clone https://github.com/AlexPanoni/Olist_Ecommerce_EDA.git
cd Olist_Ecommerce_EDA

2. Create an environment and install dependencies:
python -m venv env
# Windows
env\Scripts\activate
# macOS / Linux
source env/bin/activate
pip install -r requirements.txt

3. Place the dataset CSVs into a data/ folder (not included in repo).

4. Launch notebook:
jupyter notebook notebooks/EcommercePerformanceEDA.ipynb
