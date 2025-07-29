# 🛒 Market Basket Analysis - Association Rules Project

This project uses transactional retail data to uncover patterns in customer purchases using the **Apriori algorithm** and **Association Rules**.

---

## 📊 Objective
Identify frequently purchased item combinations and generate actionable insights for:
- Cross-selling
- Promotions
- Shelf layout optimization

---

## 🧰 Tools & Libraries
- Python
- Pandas
- mlxtend
- Seaborn / Matplotlib
- Jupyter Notebook

---

## 📁 Dataset
Columns:
- `Member_number` – Unique customer ID
- `Date` – Purchase date
- `itemDescription` – Item bought

> *Note: Dataset is anonymized and only used for academic/project purposes.*

---

## 🚀 Key Steps
1. Data Preprocessing & Transaction Creation
2. One-hot Encoding
3. Apriori for Frequent Itemsets
4. Association Rules Generation
5. Visualization of Top Rules by Lift

---

## 📈 Sample Output

### Top Rules by Lift
*(Example:)*  
`{milk} => {bread}` – Lift: **2.3**  
**Interpretation**: Buying milk increases the likelihood of also buying bread by 2.3x.

---

## 💡 Business Use Cases
- Bundle high-lift items for promotions
- Improve product placement in stores
- Personalize recommendations

---

## 📂 Files Included
- `notebook/market_basket_analysis.ipynb` – Full code
- `data/groceries.csv` – Input dataset
- `images/` – Optional visual output
- `README.md` – This file

---

## 📦 Installation

```bash
pip install pandas mlxtend matplotlib seaborn
✍️ Author
Adeline Primrose
