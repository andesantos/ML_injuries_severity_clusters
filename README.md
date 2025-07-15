# 📍 Machine Learning: Classifying Locations Based on Injury Severity
This project analyzes traffic collision data in Montgomery County, Maryland. The first part focuses on Data Prep. and the second applies machine learning clustering techniques to classify collision locations based on injury severity. The best-performing model is visualized on an interactive map.

<br>

## 📊 Project Overview
This project applies Exploratory Data Analysis (EDA) techniques to clean and prepare a dataset for the implementation of various clustering machine learning algorithms using Python. The libraries pandas, numpy, seaborn, and scikit-learn will be utilized within a Jupyter Notebook environment.

<br>

## 🧰 Tools & Technologies
Python (Jupyter Notebook)
Pandas, NumPy — for data manipulation
Matplotlib, Seaborn — for data visualization
Scikit — for machine learning models

<br>

## 🗂️ Project Structure 
  
game-sales/ <br>
├── data/ <br>
│   └── Crash_Reporting_-_Non-Motorists_Data.csv <br>
├── notebooks/ <br>
│   └── ML_injuries_severity_clusters.ipynb <br>
├── visuals/ <br>
│   └── comparison.png <br>
│   └── elbow.png <br>
│   └── k_distance_graph.png <br>
│   └── kmeans_clusters.png <br>
│   └── map_static.png <br>
│   └── results_list.png <br>
│   └── summary.png <br>
│   └── silhouette_and_bouldin_index.png <br>
│   └── traffic_critical_zones_montgomery.html <br>
├── README.md <br>
└── LICENSE

<br>

## 📌 Insights & Findings
- Silhouette score and Davies-Bouldin Index yielded somewhat conflicting results, domain knowledge guided the decision to proceed with the KMeans algorithm
- The most vulnerable points can be identified through actions such as on-site investigations to analyze physical characteristics, which can help reduce future accidents


Future improvements to this project can focus on incorporating a larger and more diverse dataset to enhance the quality of the clustering model and improve the clarity and usefulness of the visualizations.
   
<br>

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements or extensions.
