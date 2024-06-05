***Insurance Premium Prediction Project***

**Problem Statement:**
The aim of this project is to provide individuals with an estimate of their health insurance premiums based on their personal health information. This estimate can help users evaluate different insurance plans and focus on the health aspects of the policy rather than just the cost.

**Project Summary:**
** ** 
1. **Data Collection & Cleaning:**
   - Imported dataset containing health and insurance details.
   - Performed initial exploration and data cleaning including handling missing values and outliers.
   - Log-transformed the dependent variable (expenses) to normalize its distribution.
   - Removed outliers using Z-score and ensured no duplicates were present.
** **   

2. **Exploratory Data Analysis (EDA):**
   - Visualized data distributions and relationships using Seaborn and Matplotlib.
   - Key insights included:
     - Southeast region has the highest number of policyholders.
     - Smokers incur significantly higher expenses compared to non-smokers.
     - Age, BMI, and smoking status are influential factors in insurance expenses.
** **      

3. **Feature Engineering:**
   - Created dummy variables for categorical features such as sex, BMI category, number of children, smoker status, and region.
   - Transformed and scaled data to prepare for modeling.
** **    

4. **Modeling:**
   - Implemented Linear Regression to predict insurance expenses.
   - Evaluated model performance using metrics such as Mean Squared Error (MSE) and R-squared (R²).
   - Addressed multicollinearity using Variance Inflation Factor (VIF).
** **    

5. **Advanced Modeling with Neural Networks:**
   - Applied a neural network using Keras.
   - Designed a Sequential model with multiple Dense layers.
   - Trained the model and validated its performance, tracking loss and mean squared error (MSE) across epochs.
   - Visualized training and validation loss to assess model performance.
** **    

**Tools & Technologies Used:**
   - Python (Pandas, NumPy, Scipy, Seaborn, Matplotlib)
   - Scikit-Learn (for Linear Regression, train-test split, scaling)
   - Keras (for neural network implementation)
   - Google Colab (for development and execution)
** **    

**Outcome:**
   - Developed a predictive model for estimating health insurance premiums based on individual health data.
   - Identified key factors influencing insurance costs and provided actionable insights for users to better understand their insurance needs.
** **    

**Results:**
   - The Linear Regression model achieved an R-squared (R²) of 0.768.
** **    
