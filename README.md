## Customer Segmentation using K-Means Clustering

### Project Description

This project aims to group customers based on their purchasing characteristics using the **K-Means Clustering** method. This segmentation helps the company understand consumer behavior and design more targeted marketing strategies.

The dataset includes the following information:

* Sales Person Name
* Country
* Purchased Product
* Purchase Date
* Total Purchase Amount
* Number of Boxes Shipped

---

### Objectives

* Identify **customer purchasing patterns** based on volume and purchase value.
* Create **strategic segmentation** to support business and marketing decisions.
* Present clustering results in the form of **interactive and narrative visualizations**.

---

### Customer Segmentation

| Cluster | Segment Name            | Interpretation                                            | Strategic Actions                                           |
| ------- | ----------------------- | --------------------------------------------------------- | ----------------------------------------------------------- |
| **0**   | Low Volume Explorers    | Customers with low purchase amounts and infrequent orders | Product education, encourage upselling with early discounts |
| **1**   | Mass Buyers             | High volume purchases, low unit price                     | Optimize logistics, offer economic bundling                 |
| **2**   | Premium Loyalists       | Consistently purchase high-priced products                | Loyalty programs, early access to premium products          |
| **3**   | Price-Sensitive Testers | Small volume, interested in trying new products           | First-time buyer promos, A/B test for pricing strategy      |

---

### Visualizations

* Cluster Distribution per Country
  Displays the distribution of segments (Cluster 0–3) across each country using grouped bar charts.

* Products with Below-Average Sales for Three Consecutive Months
  Shows products that consistently had below-average sales from June to August, which may be prioritized for evaluation strategies.

* Monthly Average Sales Time Series
  An interactive chart showing the average monthly sales trend per product, helping to identify rising or declining trends.

* Country-wise Sales Time Series
  Interactive dropdown visualization to explore monthly sales trends per country. Users can select a country to view detailed dynamics over time.

---

### Tools & Libraries

* Python (Pandas, Plotly)
* Scikit-learn (KMeans)
* Jupyter Notebook / VS Code

---

### How to Run

1. Open the notebook `KMeans (3D).ipynb`
2. Make sure dependencies are installed: `pip install pandas plotly scikit-learn`
3. Clustering will be processed automatically → results can be visualized interactively

---
