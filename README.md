# Footly: Football Event Clustering & Analysis

This repository contains three Jupyter notebooks focused on advanced football data analysis using clustering and expected metrics (xG, xT). The project aims to uncover hidden patterns in football events using unsupervised machine learning and statistical modeling.

---

## 📁 Notebooks Overview

### 1. `footly-passing.ipynb`
Performs unsupervised clustering of passes to uncover different styles and passing patterns.  
**Key features:**
- Preprocessing of final pass event data  
- Feature engineering (location, angle, length, etc.)
- Finding the optimal number of clusters, using gap statistic
- Clustering using KMeans  
- Visualization on a football pitch and cluster interpretation

### 2. `Final_Pass_Clustering.ipynb`
Performs unsupervised clustering of passes to final 3rd to uncover different strategies of chance creation or dangerous zone penetration.
**Key features:**
- Preprocessing of final pass event data  
- Feature engineering (location, angle, length, etc.)
- Finding the optimal number of clusters, using gap statistic
- Clustering using KMeans  
- Visualization on a football pitch and cluster interpretation

### 3. `footly-xG.ipynb`
Computes **Expected Goals (xG)** values for shots using:
- Logistic regression trained on shot event data  
- Key shot features: distance, angle, shot type  
- ROC and calibration evaluation  
- Shot heatmaps and per-team xG visualization  

### 4. `footly-xT.ipynb`
Calculates **Expected Threat (xT)**, measuring how actions increase goal probability:
- Pitch division into zones  
- Value propagation using transition probabilities  
- xT assignment to various actions (passes, carries)  
- Heatmaps showing high-threat zones  

## ✨ Highlights
- 📈 Visual analytics of football metrics
- ⚽ xG and xT modeling from scratch
- 🔍 KMeans clustering to reveal passing patterns
- 📊 Football pitch heatmaps
