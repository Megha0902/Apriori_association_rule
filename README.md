
# Apriori Association Rules

## 📌 Overview

This project demonstrates how to use the **Apriori algorithm** for **market basket analysis** and building a simple **recommendation system**. The algorithm identifies frequent itemsets in transactional data and generates association rules (e.g., *“If a customer buys bread, they are likely to buy butter”*).

## 🚀 Features

* Implements the **Apriori algorithm** from scratch / using `mlxtend` .
* Generates **frequent itemsets**.
* Derives **association rules** (support, confidence, lift).
* Builds a **recommendation system** based on rules.

## 📂 Project Structure

```
Apriori_association_rule/
│-- Online_Retail.csv    # Data
│-- apriori_association_rule.ipynb        # Jupyter Notebook with code
│-- requirements.txt     # Dependencies
│-- README.md            # Project documentation
```

## ⚙️ Installation

1. Clone this repository

   ```bash
   git clone https://github.com/Megha0902/Apriori_association_rule.git
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage

Run the Jupyter notebook:

```bash
jupyter notebook apriori_association_rule.ipynb
```



## 📊 Example Output

* Frequent itemsets with support values.
* Association rules with metrics: **support, confidence, lift**.
* Recommendation examples like:

  ```
  If a customer buys {Milk, Bread} → Recommend {Butter}
  ```

## 📖 Concepts Covered

* **Support** → How often an itemset appears.
* **Confidence** → How often rule holds true.
* **Lift** → Strength of association between items.
