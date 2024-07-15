# Housing_price_prediction
Predicting housing prices using linear regression. 

## Exploration of Data

Distribution of sales price:

![image](https://github.com/user-attachments/assets/41b9638c-32a1-4309-9c1a-e277ac3f1262)

Scatterplot of living area vs sales price:

![image](https://github.com/user-attachments/assets/37ed4327-2241-4aaa-9793-a8212043fbb5)

Boxplot of overall quality vs sales price:

![image](https://github.com/user-attachments/assets/16abedb1-8ad5-4839-904b-604cef0414c8)

Correlatin Map for top 9 Variables (Heat Map):

![image](https://github.com/user-attachments/assets/3f738ab6-9f87-401d-bf66-d45042911cb3)


Pair Plot ('SalePrice', 'OverallQual', 'GrLivArea', 'GarageCars'):

![image](https://github.com/user-attachments/assets/00757ecc-db3e-4bad-8a30-86300b190077)



## Linear Regression

Linear regression models assume that the relationship between a dependent continuous variable  𝑌  and one or more explanatory (independent) variables 𝑋  is linear (that is, a straight line). It’s used to predict values within a continuous range, (e.g. sales, price) rather than trying to classify them into categories (e.g. cat, dog). Linear regression models can be divided into two main types:

### Simple Linear Regression

Simple linear regression uses a traditional slope-intercept form, where  𝑎  and  𝑏  are the coefficients that we try to “learn” and produce the most accurate predictions.  𝑋  represents our input data and  𝑌  is our prediction.

                              𝑌=𝑏𝑋+𝑎

### Multivariable Regression
A more complex, multi-variable linear equation might look like this, where w represents the coefficients, or weights, our model will try to learn.
                    
                    𝑌(𝑥1,𝑥2,𝑥3)=𝑤1𝑥1+𝑤2𝑥2+𝑤3𝑥3+𝑤0

The variables  𝑥1,𝑥2,𝑥3  represent the attributes, or distinct pieces of information, we have about each observation.


### Cost Function Graph (Simple Linear Regression)

![image](https://github.com/user-attachments/assets/3d084dbe-a79f-4a9f-9177-8f4f24a43715)


### Cost Function Graph (Multivariable Regression)

![image](https://github.com/user-attachments/assets/80b2e501-9351-44bd-9fb6-4a531aff9ea6)


![image](https://github.com/user-attachments/assets/23cbfb82-18fe-4396-8970-7beb30d34512)


![image](https://github.com/user-attachments/assets/967fc86f-0d7d-4b1a-8c26-d54da27f8396)


### Conclusion

1. Based on the cost function we can interpret that the multivarible linear regression is performing better than Simple linear Regression
2. Also, in real life we know that adding more variables can give us better estimation of the housing prices.
3. In this example, 'Above grade (ground) living area square feet' (GRlivArea - variable) is not that informative, which we can see in the simple linear regression analysis as the cost function is found to be high for predicting sales price.
4. Whereas, the variables, 'Overall material and finish quality, Above grade (ground) living area square feet and Size of garage in car capacity' can give us better prediction for sales price.



