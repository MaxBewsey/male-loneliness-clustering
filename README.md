# Exploring Patterns in Male Loneliness Using KMeans Clustering

*Completion Date: 10/07/2025*

## Overview
This project applies unsupervised machine learning to explore patterns of loneliness and emotional behaviour among men, using survey data from over 1,600 respondents. By clustering participants based on their responses to emotionally focused questions, the project identifies distinct groups with different levels of emotional openness and self-reported loneliness.

## Key Features
- Cleaned and prepared a dataset of male respondents (~30 survey questions, ~1,600 entries)
- Applied **KMeans clustering** to group men based on emotional expression and loneliness
- Introduced **age** as a feature to investigate its influence on loneliness and emotional openness
- Used **Principal Component Analysis (PCA)** to visualise clusters in reduced dimensions
- Created demographic comparisons and visualisations to interpret the emotional landscape of each group

## Methods & Tools
- **Clustering & Dimensionality Reduction:** PCA, KMeans 
- **Preprocessing:** feature scaling, standardisation  
- **Visualisation:** matplotlib, seaborn  
- **Data Handling:** pandas, numpy  

## Repo Structure
- data/
  - masculinity
- notebooks/
  - Exploring Patterns in Male Loneliness Using KMeans Clustering

## Results
- Identified **three distinct groups** with different loneliness profiles:  
  - An emotionally expressive cluster that also reported the **highest loneliness**  
  - An emotionally reserved cluster that reported the **lowest loneliness**  
  - A middle group sitting between the two extremes  
- Found that **loneliness is not simply tied to emotional openness** - those most expressive were also most likely to report loneliness.  
- Introducing age revealed a clear trend:  
  - **Younger men** were significantly more likely to report loneliness, despite greater emotional openness.  
  - **Older men** reported lower loneliness, potentially reflecting stability or reduced willingness to express distress.  

## Future Work
- Incorporate open-ended survey responses and apply **NLP techniques** for deeper insights  
- Explore **semi-supervised learning approaches** that combine structured survey responses with unstructured text data  
- Examine cultural and demographic factors that may shape self-reported loneliness  
