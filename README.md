# Franklin Wang - DIGS 30004 Final Project

# 📰 NYT Headline Clustering (2017–2020)

This project analyzes and visualizes New York Times headlines from 2017 to 2020 to uncover hidden topic patterns during the Trump presidency. Using Natural Language Processing (NLP) and machine learning techniques like TF-IDF, PCA, and K-Means clustering, we explore how news topics evolved over time. An interactive dashboard and visualizations are included to make results more accessible.

---

## 📊 Project Goals

- Cluster NYT headlines by topic using TF-IDF and K-Means
- Visualize headline similarity using PCA (2D, 3D, and scatter matrix)
- Compare topic shifts across 2017–2020
- Present findings in an interactive and informative format

---

## 🎯 Target Audience

This project is intended for:
- Researchers and scholars in media studies and digital humanities
- Journalists and data journalists
- Students studying data visualization, NLP, or political discourse

---

## 🧠 Techniques Used

- **TF-IDF (Term Frequency–Inverse Document Frequency)** to numerically represent headline text
- **PCA (Principal Component Analysis)** to reduce dimensions for visualization
- **K-Means Clustering** to group similar headlines into topical clusters
- **Word Clouds** to visualize frequent terms by year and cluster
- **Plotly & Dash** for interactive and 3D visualizations

---

## 🗂 Project Structure

nyt_headline_clustering/
│
├── data/                          # Raw CSV datasets from NYT
│   ├── new_york_times_stories_2017.csv
│   ├── new_york_times_stories_2018.csv
│   ├── new_york_times_stories_2019.csv
│   └── new_york_times_stories_2020.csv
│
├── notebooks/                     # Jupyter Notebook for analysis
│   └── nyt_headline_clustering.ipynb
│
├── visuals/                       # Output visualizations
│   ├── wordcloud_2020.png
│   ├── pca_scatter_3d.png
│   └── cluster_wordclouds/
│       ├── cluster_0.png
│       ├── cluster_1.png
│       ├── cluster_2.png
│       ├── cluster_3.png
│       └── cluster_4.png
│
├── requirements.txt              # Python dependencies
├── README.md                     # Project overview and usage
└── LICENSE                       # (Optional) License file
