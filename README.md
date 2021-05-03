# Class Profile 1A Data Analysis (with ML)

The class profile is an analysis done on students in an engineering cohort (in this case, Systems Design Engineering 2025) to display information about the class to the general public.

---

This repo contains the analysis for sections that used **machine learning algorithms** to find insights in the data

----

### Note: This is not the full repo; this repo only contains data analysis done by me using ML. To see other visualizations created by me and the rest of the team, [click here](https://github.com/SYDE-25/Class-Profile1A-Data-Analysis)

___ 

## Motivation 
- Past engineering cohorts at the university of Waterloo had already done similar projects (analyzing class data)
- To add another layer of interest to the analysis, me and my team decided that we would do a section of analysis using ML algorithms to extract insights from data   
- I wanted to put my ML skills to the test and find new things in the data... which I was able to do!

--- --------------------------------

## Tech/Framework 
 <br>
Analysis Done Using 

- Python
- Sklearn (TSNE, KMeans, PCA)
- XGBoost
- SHAP (for creating feature importance graphs)
- Yellowbrick (visualizing optimal clusters for Kmeans)
- Optuna (hyperparameter tuning for XGBoost)
- Seaborn (graphs)
- Numpy 
- Pandas (data manipulation)

## Highlights 
- Cleaning survey data using pandas, sklearn, and custom cleaning functions
- Hyperparameter tuning of an XGBoost model using Optuna 
- Extracting insights from a trained model using SHAP 
- Visualizing higher dimensional structures in data related to courses using TSNE
- Finding optimal numbers of cluster for kmeans through elbow method and silhoutte scores
- Clustering 4D course data to find data points in similar clusters

---- ------

## Notebooks

1. ML/xgb_feature_finder.ipynb for my work on finding factors that predict academic success (XGBoost + Shap)

2. ML/course_by_person.ipynb for my work on finding similar courses by clustering (TSNE + Kmeans)

## Files 
1. SYDE_2025_ML_Report_Nicolas.pdf for report containing results with insights explained

-----


## Screenshots

**Refer to graphs folder if images do not load**

Note: For analysis of the graphs, refer to **SYDE_2025_ML_Report_Nicolas.pdf** in the repo

- Feature Importance Graphs

![SHAP 1](https://github.com/Nick-palmar/class_profile_1A_data_ML_analysis/blob/main/graphs/1A_shar_bar_good.png)

![SHAP 2](https://github.com/Nick-palmar/class_profile_1A_data_ML_analysis/blob/main/graphs/shap_graph_2.jpeg)

- TSNE and Kmeans course Clustering

![TSNE by Course](https://github.com/Nick-palmar/class_profile_1A_data_ML_analysis/blob/main/graphs/1A_Course_TSNE.png)

![TSNE by Cluster](https://github.com/Nick-palmar/class_profile_1A_data_ML_analysis/blob/main/graphs/1A_Cluster_TSNE.png)

---- 

## Author 
- This data analysis was done by me - an aspiring data scientist who is always curious and looking to find insights in data 
- I would also like to thank Sean for introducing me to some of these concepts, as well as Nirmal and Alan for working with us on the data analysis for the rest of the project