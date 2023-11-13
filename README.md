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

The top 3 most impactful features in this model are:

1. Outlet_Establishment_Year
2. Outlet_Identifier_OUT045
3. Outlet_Identifier_OUT027

## **Tree-Based Model**

![download](https://github.com/sof2401/Prediction-of-Product-Sales-Project/assets/134681536/d09c0f15-af30-4fb4-9f60-661b135cf62d)

The top 5 most important features are Item_MRP, Outlet_Type_Grocery_Store, Item_Visibility, Item_Weight and Outlet_Type_Supermarket Type3.
