# Leveraging Clustering Algorithms for Optimized Customer Segmentation in Marketing Campaigns

## Description
This project demonstrates the use of machine learning clustering algorithms to optimize customer segmentation in marketing campaigns. By leveraging algorithms such as **K-Means**, **Agglomerative Clustering**, and **DBSCAN**, this system categorizes customers into meaningful segments, enabling personalized marketing strategies, improved customer engagement, and enhanced conversion rates.

---

## Features
- **Customer Segmentation Techniques**: Classify customers using demographic, behavioral, and psychographic data.
- **Comparison of Algorithms**: Evaluate clustering models using metrics such as Silhouette Score, Davies-Bouldin Index, and more.
- **Data Preprocessing**: Includes cleaning and preparation of customer datasets for optimal performance.
- **Visualization**: Visual representation of clusters and insights using tools like Power BI.
- **Scalability**: Designed to handle large datasets and provide real-time segmentation insights.

---

## Technologies Used
- **Programming Language**: Python (3.10/3.11)
- **Libraries**: NumPy, pandas, scikit-learn, matplotlib, seaborn
- **Visualization Tool**: Power BI
- **Clustering Algorithms**: K-Means, Agglomerative Clustering, DBSCAN

---

## How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Code
Execute the provided Jupyter Notebook or Python scripts to preprocess the data, train the clustering models, and visualize the results.

### 4. Visualize the Results
Use Power BI to load and visualize the processed data for further insights.

---

## Dataset
- **Source**: [Specify dataset source, e.g., Kaggle/Custom data]
- **Attributes**: Includes 21 class variables and 7044 entries.
- **Partition**: Split into training and testing datasets.

---

## Results
Our project achieved significant results in customer segmentation:
- **K-Means Clustering**: Identified customer segments with higher homogeneity, useful for predefined groups like high, medium, and low spenders.
- **Agglomerative Clustering**: Provided hierarchical relationships among customers, offering insights into nested segments.
- **DBSCAN**: Successfully identified non-linear clusters and handled outliers, making it ideal for datasets with irregular cluster shapes and noise.

### Improvements and Impact
1. **Enhanced Customer Insights**: The segmentation provided deeper insights into customer behavior, enabling businesses to understand their customers better.
2. **Targeted Marketing Campaigns**: Personalized marketing strategies based on the segments led to higher engagement and conversion rates.
3. **Efficient Resource Allocation**: Businesses could focus their marketing resources on the most promising customer groups.
4. **Real-Time Scalability**: The use of big data tools ensured scalability, enabling the system to handle large datasets effectively.

### Performance Improvements
- **Silhouette Score**: Improved by ~54% (from 0.35 to 0.54) compared to general methods.
- **Davies-Bouldin Index**: Improved by ~29% (from 1.0 to 0.71), indicating more compact clusters.
- **Marketing Conversion Rates**: Enhanced by up to **500%**, reflecting significantly better targeting and customer engagement.

---

## Future Work
- **Optimization**: Enhance DBSCAN's computational efficiency for large-scale datasets.
- **Hybrid Models**: Combine K-Means and DBSCAN for improved segmentation accuracy.
- **Expanded Data Attributes**: Include geographic and behavioral data for deeper insights.
- **Real-Time Clustering**: Develop a dynamic clustering system for ongoing marketing campaigns.

---

## Contributors
- **Jaideep S (174)**
- **Nayeem P (146)**
- **Christopher (175)**
- **Sai Nithin (171)**

---

## Acknowledgements
We extend our gratitude to our project guide, **Prof. Rashmi Benni**, for her invaluable support and guidance throughout this project. We also thank our university and all contributors to the referenced research papers for their insights.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
