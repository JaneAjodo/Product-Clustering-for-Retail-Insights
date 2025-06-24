# 🧠 Product Clustering for Retail Insights

Segmented products based on sales data using KMeans clustering and PCA.

## 📊 Dataset
- Gotten from [Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- Retail transactions: Quantity, Price, Total Sales
- Each row = a unique product

## 🔧 Process
- Removed invalid entries
- Created TotalSales = Quantity × Price
- Aggregated features per product
- Standardized features
- Used Elbow Method to select k
- Applied KMeans + PCA for 2D plotting

## 📌 Cluster Insights

| Cluster | Description |
|---------|-------------|
| 0       | Low-price, low-volume products (niche or underperforming)  
| 1       | High-volume, low-price bulk movers  
| 2       | Premium-priced low-volume products  
| 3       |  Popular mid-range products

## 📈 Tools
Python · Pandas · Scikit-learn · PCA · KMeans · Matplotlib · Seaborn

## 🔗 See Live:
- [Medium Article](https://medium.com/@janeajodo/segmenting-a-product-catalog-with-k-means-clustering-398fe3d4f000)

