# Strikers-Segmentation-Python-Project

# Football Strikers Segmentation & Performance Analysis  
**Unsupervised + Supervised Machine Learning Python Project**

## Project Overview

This repository contains a complete, fully executable **Jupyter Notebook** that uses real-world striker performance data to:

1. **Segment strikers into distinct playing styles** using **K-Means clustering**  
2. **Predict striker archetype** using **Logistic Regression** (supervised validation of clusters)  
3. Perform full exploratory data analysis, preprocessing, feature engineering, and statistical testing  
4. Visualize performance profiles (radar charts, heatmaps, cluster comparisons)

The goal: turn raw performance metrics (goals, assists, dribbling, aerial ability, defensive work, big-game performance, etc.) into **actionable player archetypes** such as:
- Clinical Finisher  
 Complete Forward  
 Poacher  
 Target Man  
 False 9 / Playmaker  
 Defensive Forward

Perfect for scouts, analysts, fantasy football enthusiasts, or anyone learning unsupervised learning in sports analytics.

## Key Outcomes

- 5–6 meaningful clusters identified (validated with silhouette score & elbow method)  
- Logistic Regression achieves **~92% accuracy** in predicting cluster membership  
- Clear performance profiles for each segment (radar charts included)  
- Statistical validation: ANOVA, Shapiro-Wilk, Levene tests  
- Bonus: Correlation analysis & feature importance

## Repository Contents

| File/Folder                        | Description                                                                 |
| 
|------------------------------------|-----------------------------------------------------------------------------|
| `SEGMENTING STRIKERS PYTHON PROJECT.ipynb` | The main notebook – fully commented, step-by-step, ready to run            |
| `data/Strikers_performance.xlsx`   | Original dataset (182 strikers × 19 performance metrics + personal info)   |
| `requirements.txt`                 | All necessary packages (pandas, scikit-learn, seaborn, matplotlib, etc.)    |
| `outputs/`                         | Saved cluster visualizations, radar charts, and model results               |
| `README.md`                        | This file                                                                   |

## How to Run (30 seconds)

```bash
git clone https://github.com/yourusername/strikers-segmentation-ml.git
cd strikers-segmentation-ml
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Open `SEGMENTING STRIKERS PYTHON PROJECT.ipynb` → Run All Cells → Explore!

Everything works out-of-the-box. No API keys, no missing files.

## Example Insights from the Analysis

- **Cluster 0: The Complete Forward** – High goals, assists, dribbling, movement, hold-up play  
- **Cluster 1: Classic Target Man – Dominant in aerial duels & hold-up, lower dribbling  
- **Cluster 3: Big-Game Poacher** – Elite conversion rate & penalty success, shines in clutch moments  
- **Cluster 4: Defensive Forward** – High defensive contribution, lower goal output  

Radar charts make comparisons crystal clear.

## Why This Project Rocks for Your Portfolio

- Real sports analytics use case (not another Iris dataset)  
- Combines unsupervised (K-Means) + supervised learning (Logistic Regression)  
- Full preprocessing pipeline: encoding, scaling, imputation, outlier handling  
- Statistical rigor (normality tests, homogeneity of variance, etc.)  
- Beautiful, publication-ready visualizations  
- Clean, well-commented code that actually tells a story


