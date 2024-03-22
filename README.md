# ML_Final_Project🏀


We aim to develop a machine learning predictive model to estimate the likelihood of NBA players being chosen as All-Stars. The selection process for All-Star starters from both the Eastern and Western Conferences relies on a weighted distribution of votes: 50% from fans, 25% from fellow players, and 25% from members of the media. Conversely, reserve players are selected based on the combined votes of NBA coaches.

Our project will primarily focus on analyzing player data from each season spanning 1951 to 2023. While player performance does not directly determine the All-Star selections, it indirectly influences the decisions of fans, players, and the media.

## Packages Used

* XGBoost - Gradient boosting framework



## Machine Learning and Predicting NBA All-Star Players

Machine learning (ML) contributes significantly to predictive modeling. In this project, we have chosen to predict NBA All-Star players using various Machine learning tools, such as clustering.

## Project Workflow


### Methodology for Handling Missing Values & Data Cleaning

1. #### Handling Missing Values
Missing values were addressed through imputation techniques such as mean, median, or mode imputation, or by removing rows/columns with missing values based on the nature of the data and the extent of missingness.

2. #### Data Cleaning
Data cleaning involved tasks such as removing duplicates, correcting inconsistencies, and ensuring data integrity. This step aimed to prepare the data for further analysis and modeling.

3. #### Data Preparation and Feature Scaling
After cleaning the data, it was prepared for modeling by encoding categorical variables and scaling numerical features. Feature scaling techniques like Min-Max scaling or standardization were applied to ensure that all features contributed equally to the model.

4. #### PCA Data Frame
Principal Component Analysis (PCA) was performed to reduce the dimensionality of the data while preserving its variance. This step aimed to capture the most important patterns in the data and improve computational efficiency.

5. #### Optimal n for Clustering
The optimal number of clusters for clustering algorithms like K-means or hierarchical clustering was determined using methods such as the elbow method or silhouette score analysis. This helped identify the appropriate granularity for grouping similar data points together.

6. #### Models with Clustering
Models were trained and evaluated using both the original dataset and the dataset with additional cluster labels. The clustering labels were incorporated as additional features to assess their impact on model performance.

1. ##### KMeans
KMeans clustering was applied to partition the data into distinct clusters based on similarities between data points. Models were  trained using features extracted from the KMeans clusters.

2. ##### Hierarchical Cluster
Hierarchical clustering was used to create a hierarchy of clusters based on the pairwise distances between data points. The resulting clusters were then utilized as features for model training and evaluation.


7. **Anomaly Removal:** Identifying and removing anomalies to improve the model's accuracy.

### Limitations

1. **Data Imbalance:** The model faces challenges due to the significant disparity in the number of regular players and All-Star players. This may lead to biased predictions
2. **Evaluation Bias:** The evaluation metrics may be affected by the data imbalance, requiring additional techniques or sampling strategies to mitigate bias.

### Conclusion

By combining various machine learning techniques, we aim to develop a predictive model capable of accurately identifying NBA All-Star players. Acknowledging data imbalances and limitations is crucial, and continuous refinement and evaluation will be employed to achieve optimal results.
