# Prediction of Product Sales Project
## Project Overview

In this project, we are cleaning the 'Prediction of Product Sales' dataset and using it for analysis purposes. This includes but isn't limited to exploratory data analysis and feature inspection.

## Data Visualizations

1. The heatmap below illustrates how different features in the data frame are connected. I've included labels in each box to provide more information about the specific correlation values and enhance the overall understanding of the graph.

![heatmap](https://github.com/sof2401/Prediction-of-Product-Sales-Project/assets/134681536/3269619d-42cb-41f6-a586-a71c8d4f0e39)

2. The bar graph below shows how many of each item type exists in the data frame. This type of graph benefits stakeholders because it is easy to identify critical details such as max, min, and the relationship between the quantities of their products.

![bar graph](https://github.com/sof2401/Prediction-of-Product-Sales-Project/assets/134681536/5b6424f1-1b1e-4ad2-ae7f-2c467176aa1a)



## **For the Stakeholders**

Overall, the model that performed the best was the GridSearchCV model. It gave us the highest R^2 values for the testing data. The MAE, MSE, and RMSE are also closer to one of the other models, which further shows us that this model is excelling in performance compared to the other models.

<img width="545" alt="Screenshot 2023-11-10 at 7 54 17 AM" src="https://github.com/sof2401/Prediction-of-Product-Sales-Project/assets/134681536/35e4b0d3-fa89-4b82-9f16-b390839123a5">

## **Linear Regression Model**

<img width="542" alt="Screenshot 2023-11-10 at 8 49 58 AM" src="https://github.com/sof2401/Prediction-of-Product-Sales-Project/assets/134681536/5b19f531-7419-4eeb-9444-1c6cea6803d1">

From the linear regression model, we can see that the coefficients modeled in our linear regression model are able to provide an R^2, in our testing metrics, of 0.567.

## **Tree-Based Model**

<img width="543" alt="Screenshot 2023-11-10 at 8 58 40 AM" src="https://github.com/sof2401/Prediction-of-Product-Sales-Project/assets/134681536/0e8414e8-22af-4909-b831-8a003bd8905c">

Our bagging regressor model offers us a better performance in the testing data, with an R^2 of 0.580. 
