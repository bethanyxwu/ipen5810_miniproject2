# ipen5810_miniproject2
miniproject2-Free International Trade
repository for ipen5810

//////////////////////////////////////////////////////////////////////////////// FILES FOR: // Mini Group Project Ⅱ - Free International Trade - IPEN 5810 // by Xinyu, WU & Chengyue, LAI // date: 7 May 2024 // ////////////////////////////////////////////////////////////////////////////////

**Project Overview:**
This repository contains our group's submission for the Mini Project II in the Data Science in Empirical Economics course at IPEN 5810. Our project investigates international trade flows by analyzing a comprehensive dataset, utilizing data science and econometric techniques to uncover patterns, relationships, and predictive insights into trade dynamics.

**Project structure:**
problem1_2.ipynb: Contains our work on descriptive analysis and initial data preprocessing using Dask, including:
1.1.Top and bottom 10 countries by number of trading partners.
1.2.Trade volume analysis matched by product and country codes.
1.3.Top 10 exports analysis for the USA, EU, China, and Vietnam.
1.4.Calculation of distances using geopandas and creation of scatterplots of distance vs. export volume.

2.1. Calculate 27 characteristic indicators
2.2 Using PCA to extract principal components and specific explanatory feature variables for k-means clustering
2.2 Application of K-means clustering to identify distinct groups based on trade characteristics.
2.3 Perform k-means clustering analysis
2.4 Analyze and visualize k-means clustering results and extract potential economic issues

problem3.ipynb: Focuses on applying machine learning to predict trade flows and unsupervised learning techniques to identify trade patterns among countries. Includes:
3.1 Machine learning model development to predict export quantities and evaluate the model's performance

mini2.pptx：Including the answer to the bonus question, we attempt to use econometric methods to verify which type of sector is distance most in terms of exporting

**Main findings and conclusions:**
1. The k-means clustering divides countries into four categories based on the ten extracted features
2. Preliminary evidence suggests a negative correlation between export distance and export diversity
3. The trade model of a trading power has stability, with concentrated numerical distribution of various characteristics and fewer outliers
