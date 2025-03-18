#  House Price Prediction using Multiple Regression Models

## 1. Introduction
- **Problem Statement:** Predict house prices based on various features such as house size, number of bedrooms, and age of the house using regression models.
- **Objectives:**  
  - Understand and apply machine learning regression techniques.  
  - Build and evaluate different models like Linear Regressionand Decision Tree.  
  - Visualize and interpret relationships between features and house prices.  

---

## 2. Methodology

### Dataset
- **Source:** Synthetic dataset created for project demonstration.  
- **Characteristics:**  
  - **Features:**  
    - House Size (in square feet)  
    - Number of Bedrooms  
    - Age of the House (in years)  
  - **Target:** House Price  
  - **Number of samples:** 100 data points  

---

### Data Preprocessing
- **Handling missing values:** No missing values were present in the dataset.  
- **Normalization:** Applied **StandardScaler** for scaling features when required (e.g., in Polynomial Regression).  

---

### Models Used
| Algorithm                    | Description                                         |
|-----------------------------|----------------------------------------------------|
| **Linear Regression**        | Baseline model to understand linear relationships. |
| **Decision Tree Regressor**  | Tree-based model for non-linear pattern learning. |

- **Libraries Used:**  
  - scikit-learn  
  - pandas  
  - matplotlib, seaborn (for visualization)  
- **Training-Testing Split Ratio:** 65% Training, 35% Testing.  

---

### Evaluation Metrics
- **Mean Squared Error (MSE)**  
- **R² Score (Coefficient of Determination)**  

---

## 3. Results

### Evaluation Metrics Comparison

| Model                   | MSE       | R² Score  |
|------------------------|-----------|-----------|
| **Linear Regression**   | 26.18     | 0.71      |
| **Decision Tree**       | 22.11     | 0.76      |

---

### Visualizations
- **Scatter plots** showing relationships between house size, bedrooms, age, and price.
- **Regression lines** and **Decision Tree splits** visualized for better interpretation.
- **Residual plots** to assess model fit.

---

## 4. Discussion

### Interpretation of Results:
- **Linear Regression** performed similarly, explaining about 70% of variance in house prices.
- **Decision Tree Regressor** performed well (R² ≈ 0.76), but may overfit on small datasets if not tuned properly.

### Challenges Faced:
- Limited dataset size restricted the complexity of models that could be applied.
- Risk of overfitting with high-degree polynomial features.
- Feature scaling was critical to stabilize Polynomial Regression.

---

## 5. Conclusion

### Summary of Findings:
- **Linear models provided a good baseline with R² ≈ 0.71.
- **Decision Tree Regressor** showed promising results but requires tuning for optimal performance on small datasets.

### Potential Improvements:
- Collect more data for robust model training.
- Include additional features like:
  - Location (city, neighborhood)
  - Proximity to amenities (schools, hospitals)
  - House condition and type.
- Explore advanced models like **Random Forest**, **Gradient Boosting**, or **XGBoost**.
- Perform cross-validation for more reliable evaluation.

---

## 6. References
- **Dataset:** Boston Housing Dataset.  
- **Libraries & Tools:**  
  - [scikit-learn](https://scikit-learn.org/)  
  - [pandas](https://pandas.pydata.org/)  
  - [matplotlib](https://matplotlib.org/)  
  - [seaborn](https://seaborn.pydata.org/)

---

## Author:
- **Atharva Shelke**, Computer Engineering Student, Passionate about Machine Learning and Data Science.
