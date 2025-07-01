# 🚀 Customer Segmentation Dashboard

Unlock insights from the Survey of Consumer Finances (SCF) with interactive clustering and visual analytics! 🧑‍💼💰📊

---

## 📋 Project Overview
This project segments customers using the SCF dataset, revealing patterns in financial and demographic data. It combines data science techniques—exploratory analysis, feature engineering, and unsupervised machine learning—with a beautiful interactive dashboard for hands-on exploration.

---

## ✨ Features
- 📥 **Loads & preprocesses** the SCF dataset
- 👀 **Explores** demographics (age, race, income, assets, etc.)
- 📊 **Visualizes** distributions & correlations (matplotlib, seaborn, plotly)
- 🔍 **Identifies** high-variance features for clustering
- 🤖 **Clusters** customers with K-Means & evaluates with inertia/silhouette scores
- 🧬 **Reduces dimensionality** with PCA for 2D visualization
- 🖥️ **Interactive dashboard** (Dash/JupyterDash) to explore features & clusters

---

## 🛠️ Requirements
- Python 3.8+
- Jupyter Notebook or JupyterLab
- dash==2.14.2
- jupyter-dash==0.4.2
- pyngrok
- pandas
- plotly
- matplotlib
- seaborn
- scikit-learn
- scipy

_Install all dependencies with:_
```bash
pip install dash==2.14.2 jupyter-dash==0.4.2 pyngrok pandas plotly matplotlib seaborn scikit-learn scipy
```

---

## 🚦 Quick Start
1. **Download the SCF dataset** and place it as `/content/scfp2019excel.zip` (or update the path in the notebook).
2. **Open** `customer_segmentation.ipynb` in Jupyter.
3. **Run all cells** to:
   - Analyze the data
   - Visualize key features
   - Launch the interactive dashboard

---

## 🖼️ Dashboard Highlights
- 🎚️ **Toggle** between trimmed/untrimmed variance for feature selection
- 🔢 **Adjust** the number of clusters (k) for K-Means
- 📈 **View** inertia & silhouette metrics
- 🧩 **Explore** clusters in 2D with PCA scatter plots

The dashboard runs in your browser via JupyterDash. Perfect for data storytelling and exploration! 🌟

---

## 📦 Repo Structure
- `customer_segmentation.ipynb` — Main notebook (analysis + dashboard)
- `README.md` — You are here!

---

## 🙌 Credits
- Data: [Survey of Consumer Finances (SCF)](https://www.federalreserve.gov/econres/scfindex.htm)
- Built with ❤️ using Python, Dash, and Jupyter

---

## 📄 License
MIT (or specify your license here)

---

Happy clustering! 🚀
