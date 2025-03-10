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

- data/ 
This folder contains the raw datasets used in the project. Specifically, it holds the CSV files of New York Times headlines from 2017 to 2020:
  - new_york_times_stories_2017.csv
  - new_york_times_stories_2018.csv
  - new_york_times_stories_2019.csv
  - new_york_times_stories_2020.csv

- notebooks/ </br>
This directory includes the main Jupyter Notebook file used for data preprocessing, TF-IDF transformation, PCA dimensionality reduction, clustering, and visualization:
  - nyt_headline_clustering.ipynb

- app/
Contains the interactive Dash web application for exploring the PCA visualizations and cluster results:
- app.py
  
- visuals/
Stores the output visualizations generated during the project. These include:
- Word clouds for individual years and clusters
- PCA scatterplots (e.g., 2D or 3D)
- Subfolder cluster_wordclouds/ which contains word cloud images for each K-Means cluster (e.g., cluster_0.png, cluster_1.png, etc.)

- requirements.txt
  A list of Python dependencies needed to run the code and app (e.g., pandas, scikit-learn, plotly, dash, etc.)

- README.md
This file provides an overview of the project, including objectives, methods, visualizations, usage instructions, and documentation.

- LICENSE
An optional file specifying the license for my project.
