# ML_Final_Project🏀

## Packages Used


* Tensorflow - Machine learning library
* XGBoost - Gradient boosting framework
  
## Limitations
Unbalanced class: There have only been 30 college players drafted into the NBA that have made an All-Star game since 2008. Therefore, our target class is approximately 5% of our data. Given the already small size of our dataset, this could make it difficult for our model to learn enough information from our features to create an accurate prediciton.


## Machine Learning and Predicting NBA All-Star Players

Machine learning (ML) contributes significantly to predictive modeling. In this project, we have chosen to predict NBA All-Star players using various machine learning tools, such as clustering.

### Data Imbalance and Limitations

**Data Imbalance:**
The dataset exhibits a significant imbalance, with a considerably larger number of regular players compared to All-Star players. This imbalance may impact the model's ability to accurately predict All-Star selections.

**Prediction Methodology:**
- **Logistic Regression:** A baseline model for predicting All-Star players based on player statistics.
 
- **Clustering:** Utilizing clustering techniques to group players based on shared characteristics, enhancing predictive capabilities.
 
- **Anomaly Detection:** Identifying and handling outliers to improve overall model accuracy.

- **Evaluation:** Employing metrics such as precision, recall, and F1-score to assess the model's effectiveness.

### Project Workflow

1. **Data Cleaning:** Removing irrelevant features, handling missing values, and ensuring data quality.
 
2. **Exploratory Data Analysis (EDA):** Visualizing relationships between features, identifying outliers, and understanding data correlations.

3. **Feature Engineering:** Creating new features, like Player Efficiency Rating (PER), to enhance predictive capabilities.

4. **Model Training:** Employing logistic regression, clustering, and anomaly detection to build a robust predictive model.

5. **Evaluation:** Assessing model performance using precision, recall, and F1-score.

6. **Anomaly Removal:** Identifying and removing anomalies to improve the model's accuracy.

### Limitations

1. **Data Imbalance:** The model faces challenges due to the significant disparity in the number of regular players and All-Star players. This may lead to biased predictions.

2. **Evaluation Bias:** The evaluation metrics may be affected by the data imbalance, requiring additional techniques or sampling strategies to mitigate bias.

### Conclusion

By combining various machine learning techniques, we aim to develop a predictive model capable of accurately identifying NBA All-Star players. Acknowledging data imbalances and limitations is crucial, and continuous refinement and evaluation will be employed to achieve optimal results.
