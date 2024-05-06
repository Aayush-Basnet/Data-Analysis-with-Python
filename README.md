# Data-Analysis-with-Python
 Data analysis with Python to building and evaluating data models


--------------------------------------------------------------------------------
## Data Analysis with Python

Tasks          | Topic       | Content Included
-------------- | ------------|-------------------
[Task 1](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/main/Task%201%20Used%20Car%20Pricing/Used_Car_Pricing.ipynb)      | User Car Pricing  | Data Wrangling: Handling missing values, Data Fromat, Data Standardization, Data Normalization, Binning and Indicator variable
[Task 2](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/main/Task%202%20EDA%20Laptops%20Pricing%20Dataset/EDA-%20Laptops%20Pricing%20Dataset.ipynb)     | Laptops Pricing  | EDA, groups and pivot tables, Pearson Correlation
[Task 3](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/main/Task%203%20Model%20Development%20Car%20Pricing/Model%20Development_automobile.ipynb)     | automobile Price  | Model Development; Linear Regression, Polynomial Regression, Pipeline, Visualization, R-square, Mean Square Error, Prediction & Decision Making
[Task 4](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/main/Task%204%20Model%20Development%20Laptop%20Pricing/model_development_laptopspricing.ipynb)   | Laptop Pricing   | Model Development, Linear Regression, Polynomial Regression, Pipeline, Plot
[Task 5](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/tree/main/Task%205%20Model%20Evaluation%20automobile%20pricing)    | automobile pricing  | Model Evaluation, overfitting, Ridge Regression, Cross validation, Grid Search 
-----------------------------------------------------------------------------------------------------
# Task 1: Used Cars Pricing

Objectives:
* Handling missing values
* Correct data formatting
* Standardize and normalize data

# Table of Contents
1. Identify missing values
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/missing%20value%201.1.png)
   * Deal with missing values
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/missing%20value%201.2.png)
   * Correct data format
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/missing%20vaule%201.3.png)
3. Data Standardization
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/standardization.png)
4. Data Normalization
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/normalization.png)
5. Binning
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/bining%201.2.png)
6. Indicator variable
 ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/fa1a25d97dce2563248c2b6fe73bced16978e8f4/Image/Indicator%20variable_%20dummies.png) 

We use data wrangling to convert data from an initial format to a format that may be better for analysis.

---------------------------------------------------------------------------

# Task 2 : Laptops Pricing Dataset

Objectives:
* Visualize individual feature patterns
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/2712f63f0ba818bdd826a8c227f8a803eaf88798/Image/regplot.png)
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/2712f63f0ba818bdd826a8c227f8a803eaf88798/Image/boxplot.png)
* Run descriptive statistical analysis on the dataset
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/2712f63f0ba818bdd826a8c227f8a803eaf88798/Image/description.png)
* Use group and pivot tables to find the effect of categorical varaibles on price
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/2712f63f0ba818bdd826a8c227f8a803eaf88798/Image/group%20and%20pivot%20table.png)
* User Pearson Correlation to measure the independence between variables
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/2712f63f0ba818bdd826a8c227f8a803eaf88798/Image/Pearsonlaw.png)

----------------------------------------------------------------------------------------------------------------------------------------------

# Task 3 : Model Development; automobile pricing

Objectives: 
Develop prediction models

In this task, I'll develop several models that will predict the price of the car using the variables or features. This is just an estimate but should give us an objective idea of how much the car should cost.

* Simple Linear Regression
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/a9f42b7faee1f3ba4a4ce3aa29b1c6cf17ea2b71/Image/Task%203_LinearRegression.png)
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/a9f42b7faee1f3ba4a4ce3aa29b1c6cf17ea2b71/Image/Task%203_ResidualPlot.png)
* Multiple Linear Regression
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/a9f42b7faee1f3ba4a4ce3aa29b1c6cf17ea2b71/Image/Task%203_DistributionPlot.png)
* Pipeline
  ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/a9f42b7faee1f3ba4a4ce3aa29b1c6cf17ea2b71/Image/Task%203_Pipeline.png)
* Conclusion
 ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/a9f42b7faee1f3ba4a4ce3aa29b1c6cf17ea2b71/Image/Task%203_Conclusion.png)


------------------------------------------------------------------------------------

# Task 4: Model Development- Laptop Pricing

### Objectives
* Use Linear Regression in one variable to fit the parameters to a model
* Use Linear Regression in multiple variables to fit the parameters to a model
* Use Polynomial Regression in single variable to fit the parameters to a model
* Create a pipeline for performing linear regression using multiple features in polynomial scaling
* Evaluate the performance of different forms of regression on basis of MSE and R^2 parameters.

  * Simple Linear Regression
 ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/0f2202fd2504687b2243169b79fd0786193d04ac/Image/Task4_slr.png)

  * Multiple Linear Regression
 ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/0f2202fd2504687b2243169b79fd0786193d04ac/Image/Task4_mlr.png)

  * Polynomial Regression
 ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/0f2202fd2504687b2243169b79fd0786193d04ac/Image/Task4_polyregression.png)

  * Pipeline
    ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/0f2202fd2504687b2243169b79fd0786193d04ac/Image/Task4_pipeline.png)


--------------------------------------------------------------------------------------------------------------------------------------

# Task 5: Model Evaluation and Refinement: automobile pricing

## Objectives
* Evaluate and refine prediction models

### Tables of Contents

 * Model Evaluation
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/4c58e2824267a28b9fa33d9de6d6cdcef2b0beb3/Image/Task%205%20train_test.png)
 * Cross validation
   ![alt tex](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/4c58e2824267a28b9fa33d9de6d6cdcef2b0beb3/Image/Task%205%20cross%20validation.png)
 * Over-fitting, Under-fitting and Model Selection
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/4c58e2824267a28b9fa33d9de6d6cdcef2b0beb3/Image/Task%205%20overfitting.png)
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/4c58e2824267a28b9fa33d9de6d6cdcef2b0beb3/Image/Task%205%20overfitting%20figure.png)
 * Ridge Regression
   ![alt text](https://github.com/Aayush-Basnet/Data-Analysis-with-Python/blob/4c58e2824267a28b9fa33d9de6d6cdcef2b0beb3/Image/Task%205%20Ridge.png)
 * Grid Search
   
