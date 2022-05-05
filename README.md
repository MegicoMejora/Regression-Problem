# Multi Linear Regression-Problem

The important steps involved are,

1. Data Preprocessing

2. Outlier Detection

3. Feature Engineering

4. Feature scaling

5. Model Building

## 1. Data Preprocessing

Data were cleaned and converted features having categorical labels to numerical labels by doing One hot encoding.

## 2. Outlier Detection

Outliers were detected and removed using Z-Score.

## 3. Feature Engineering

Data Transformation was done for few features which are not normally distributed. As the samples have negative values, feature 'F14' is transformed using Power Transformer. Feature 'f15' is transformed by Square Root Transformation.

## 4. Feature Scaling

Standardized the data using StandardScaler

## 5. Model Building

After experimenting with number of Machine learning algorithms, selected best models for this dataset are,

1.Linear Regression

2.Lasso Regression

3.Support Vector Regressor (SVR)

## 5.1 Linear Regression 

Linear Regression model was selected after validating The Coefficient of Determination R square value. 

Linear Regression Assumptions were checked.

  ### 1. Independence of obsevations - there is no hidden relationship between observations.
  
  ### 2. Linear Relationship 
  
          
  ### 3. Multivariate Normality
  
          Features 'f14' and 'f15' are not not normally distributed. These feature were transformed using Suare root transformation and Power transformer.
          
  ### 4. Multicolinearity
  
            No mulicolinearity was present checked using Variance Inflation Factor.
            
  ### 5. AutoCorrelation 
 
          Checked using Durbin-Watson test. No autocorrelation was present.
          
  ### 6. Normal Distribution of Residuals

        The residuals were normally distributed
        
  ### 7. Heteroscedascity
  
        There is no Heteroscedasticity present as the samples were not following any pattern.
 
 
  
            
          
        
