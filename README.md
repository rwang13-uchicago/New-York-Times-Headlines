# Franklin Wang - DIGS 30004 Final Project
(Credit: The following READ ME file is generated with some help from ChatGPT.)

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

- data/ </br>
This folder contains the raw datasets used in the project. Specifically, it holds the CSV files of New York Times headlines from 2017 to 2020:
  - new_york_times_stories_2017.csv
  - new_york_times_stories_2018.csv
  - new_york_times_stories_2019.csv
  - new_york_times_stories_2020.csv

- notebook/ </br>
This directory includes the main Jupyter Notebook file used for data preprocessing, TF-IDF transformation, PCA dimensionality reduction, clustering, and visualization:
  - nyt_headline_clustering.ipynb
  
- visuals/ </br>
Stores the output visualizations generated during the project. These include:
  - Word clouds for individual years and clusters
  - PCA scatterplots (e.g., 2D or 3D)
  - Subfolder cluster_wordclouds/ which contains word cloud images for each K-Means cluster (e.g., cluster_0.png, cluster_1.png, etc.)

- requirements.txt </br>
  A list of Python dependencies needed to run the code and app (e.g., pandas, scikit-learn, plotly, dash, etc.)

- README.md </br>
This file provides an overview of the project, including objectives, methods, visualizations, usage instructions, and documentation.

---

## 🛠️ Installation Instructions

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/nyt-headline-clustering.git
cd nyt-headline-clustering
```

### 2. (Optional) Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install required Python packages

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt` yet, you can create one with the following:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
plotly
wordcloud
dash
```

---

## 🚀 Usage Guide

### ▶️ To run the main notebook:

Open the file `nyt_headline_clustering_cleaned.ipynb` using Jupyter Notebook, JupyterLab, or VS Code with the Jupyter extension. Run all cells to execute:

- Data loading (NYT headlines from 2017–2020)
- Text cleaning and TF-IDF transformation
- Dimensionality reduction using PCA
- Clustering using K-Means
- Multiple visualizations (PCA scatter plots, word clouds, elbow method)
- Critical analysis and findings
