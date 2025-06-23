# 📊 B3 Stock Clustering with KMeans

This project applies unsupervised machine learning — specifically KMeans clustering — to segment stocks listed on the Brazilian stock exchange (B3) into distinct groups based on financial characteristics. The goal is to uncover natural groupings in the market that can support portfolio decisions, screening strategies, or exploratory financial analysis.

---

## 🧠 Project Objective

The main objective is to group B3-listed companies into clusters based on key financial metrics such as:

- Market Capitalization
- Dividend Yield
- Annualized Return
- Beta

These clusters help identify patterns and similarities among companies beyond industry labels or market sectors.

---

## ⚙️ Technologies & Libraries Used

- Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn

---

## 📂 Dataset

The dataset includes fundamental metrics of publicly traded companies from B3. These include market cap, beta, dividend yield, and returns — normalized before clustering. (Additional sources can be merged for future work.)

---

## 📌 Methodology

1. **Data Preprocessing**: Cleaning, normalization, and feature selection.
2. **Elbow Method & Silhouette Score**: Used to determine the optimal number of clusters.
3. **KMeans Clustering**: Performed on scaled numerical features.
4. **2D Visualizations**: Scatter plots and bar charts to interpret and validate the formed clusters.

---

## 🔍 Cluster Interpretations

- **Cluster 0**:  
  High dividend yield, low return, moderate-to-high beta. Income-oriented, mature firms.

- **Cluster 1**:  
  Moderate dividend yield, steady return, low market cap, low beta. Small-cap, stable-growth firms.

- **Cluster 2**:  
  Low dividend yield, higher return, mid-sized market cap, low beta. Growth-oriented companies.

- **Cluster 3**:  
  Very large market caps, strong dividends, high return, moderate-to-high beta. Blue-chip or market leaders.

---

## 📈 Visual Analysis

The notebook includes multiple visualizations:
- Elbow plot and silhouette scores
- Average metrics per cluster
- 2D scatter plots for variable interactions

These allow deeper insights into the behavior and distinction of each group.

---

## ✅ Conclusion

Clustering revealed meaningful patterns in the B3 market using just a few financial features. The project shows how unsupervised learning can help structure large datasets and inform investment strategies.

---

## 🚀 Next Steps

- Include more B3-listed companies for better generalization.
- Add more financial ratios (P/E, P/B, ROE, etc.).
- Explore other clustering algorithms (DBSCAN, Agglomerative).
- Benchmark clusters against international stocks.
- Incorporate time-series features or momentum indicators.
