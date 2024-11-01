# NBA MVP Prediction Project

### Overview
This project is one of my early AI programs, completed in March 2022. It focuses on predicting NBA MVP rankings by analyzing player statistics from previous seasons.

### Motivation
- Passion for basketball and analytics
- Desire to explore AI's predictive capabilities in sports
- Potential applications in sports betting and forecasting

### Methodology
1. **Data Cleansing**: Cleaned and processed the raw NBA player data, handling missing values and standardizing columns for analysis.
2. **Predicting Columns**: Selected specific player statistics as predictors, focusing on metrics likely to influence MVP selection.
3. **Training and Testing**: Split the data into training and testing sets to evaluate model performance effectively.
4. **Ridge Regression Model**: Initially used Ridge Regression (a regularized form of linear regression) to mitigate overfitting by shrinking correlation coefficients.
5. **Concatenating Data**: Combined predictions with actual data to compare results and fine-tune model accuracy.
6. **Visual Data Display**: Generated visualizations, including correlation heatmaps, to understand relationships between variables.
7. **Error Metrics**: Calculated Mean Squared Error (MSE) and Average Precision Score (APS) to assess prediction accuracy.
8. **Backtesting**: Applied backtesting by training on past seasons and testing on future ones, ensuring robustness across different years.
9. **Data Scaling**: Used `StandardScaler` to normalize data, improving model consistency and accuracy.
10. **Random Forest Model**: Implemented a Random Forest model, which creates and averages multiple decision trees, yielding an 85% accuracy rate in MVP predictions.

### Results
- The model achieved around 85% accuracy in predicting MVP standings.
- Top-ranked players like Nikola Jokić, Joel Embiid, and Stephen Curry were closely matched to their actual MVP rankings.
- Differences between actual and predicted rankings helped refine the model's performance metrics.

### Future Directions
- Further improvements in model accuracy with feature engineering and hyperparameter tuning
- Potential to expand the model to other sports and integrate it into a mobile app

### Sample Output
| Player                | Actual Rank | Predicted Rank | Difference |
|-----------------------|-------------|----------------|------------|
| Nikola Jokić          | 1           | 3              | -2         |
| Joel Embiid           | 2           | 2              | 0          |
| Stephen Curry         | 3           | 5              | -2         |
| Giannis Antetokounmpo | 4           | 1              | 3          |
| Chris Paul            | 5           | 33             | -28        |

### Conclusion
This project was a valuable learning experience in applying AI and machine learning to real-world data, particularly in sports analytics. The model’s strong performance in predicting MVP candidates demonstrated the power of AI in interpreting complex datasets.
