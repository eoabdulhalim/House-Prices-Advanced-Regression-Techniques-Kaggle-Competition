# House-Prices-Advanced-Regression-Techniques-Kaggle-Competition

# (Rank: 1675/4818) Top 35% - Beating More Than 65%

🔍 **Data Cleaning & EDA:**
To ensure the data was in the best possible shape, 
I conducted thorough **data cleaning and Exploratory Data Analysis (EDA)
** using **Plotly** for interactive visualizations. This helped me to:
- Identify and handle outliers effectively
- Address missing values
- Understand the distribution of features and target variable

💡 **Feature Engineering:**
I applied **feature engineering** to create new features and enhance existing ones. 
By analyzing feature importance, I manually selected only the most important features 
to improve the model's performance.

🔍 **Models Used:**
1. **Linear Regression:**
   - **Accuracy:** 93%
   - **RMSE:** 23,003
2. **Elastic Net:**
   - **Accuracy:** 93%
   - **RMSE:** 23,016
3. **Gradient Boosting:**
   - **Accuracy:** 92%
   - **RMSE:** 23,765
4. **Stacking Regressor (Elastic Net + Gradient Boosting):**
   - **Accuracy:** 93.6%
   - **RMSE:** 22,090

After experimenting with various models, 
I decided to go with a **Stacking Regressor** combining Elastic Net and Gradient Boosting. 
This approach led to an impressive **accuracy of 93.6%** and a **RMSE of 22,090**,
which significantly boosted my performance.
