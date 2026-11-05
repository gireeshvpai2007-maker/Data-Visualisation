<div align="center">

# 📊 Data Visualisation

**Exploratory data analysis and visual storytelling with Python**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/> <img src="https://img.shields.io/badge/Seaborn-5B8FA8?style=flat-square"/>

</div>

## Overview

A collection of notebook-based EDA projects that use data cleaning, statistical summaries, and visualizations to explore patterns in datasets.

## Project gallery

### Emotion analysis

Explores emotion labels and their distribution, with a word cloud as a compact visual summary.

<p align="center"><img src="Emotion%20Analysis/image/wordcloud.png" width="78%" alt="Word cloud from emotion analysis"/></p>

**Notebook:** `Emotion Analysis/notebook/Emotion.ipynb`

### Online learning engagement

Investigates engagement data and its relationship with student outcomes using exploratory and correlation analysis.

<p align="center"><img src="Online%20Learning%20Engagement%20Analysis/image/correlation%20heatmap.png" width="78%" alt="Correlation heatmap for online learning engagement"/></p>

**Notebook:** `Online Learning Engagement Analysis/notebook/dproject.ipynb`

## Analysis workflow

```text
Load dataset → Inspect and clean → Explore distributions
                                  ↓
                         Compare relationships
                                  ↓
                         Visualize and interpret
```

## Repository structure

```text
Data-Visualisation/
├── Emotion Analysis/
│   ├── dataset/
│   ├── image/
│   └── notebook/
├── Online Learning Engagement Analysis/
│   ├── dataset/
│   ├── image/
│   └── notebook/
├── requirements.txt
└── README.md
```

## Run locally

```bash
git clone https://github.com/gireeshvpai2007-maker/Data-Visualisation.git
cd Data-Visualisation
pip install -r requirements.txt
jupyter notebook
```

Open either project notebook and run its cells. Dataset and image paths are relative to the repository.

## Tools and techniques

- **Data preparation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, WordCloud
- **Exploration:** distributions, descriptive statistics, relationships, and correlation heatmaps

## Next steps

- Add interactive charts and a dashboard
- Extend the analysis with additional datasets and statistical tests
- Document concise findings alongside each visualization

---

<div align="center">
<i>Turn data into patterns you can see—and questions worth asking.</i>
</div>