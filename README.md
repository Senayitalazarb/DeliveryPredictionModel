# Delivery Duration Prediction - DoorDash

## Introduction
The aim of this project is to develop a model to predict the estimated time taken for a delivery when a consumer places an order on DoorDash. Accurate delivery time predictions are crucial for ensuring a positive consumer experience. Therefore, it is essential to develop a reliable model that can help DoorDash estimate delivery times accurately.

## Data
The dataset used in this project contains delivery data for DoorDash, including features such as pickup and dropoff locations, pickup and delivery times, and the expected delivery duration in seconds. The dataset is split into training and testing datasets to train and evaluate our models.

## Methodology
We started by exploring and visualizing the dataset to gain insights into the relationships between the features and the target variable. Next, we preprocessed the data by scaling and reducing the number of features using PCA. Then, we trained and evaluated several regression models, including Linear Regression, Random Forest Regression, and Decision tree regression. We used various performance metrics such as Root Mean Squared Error (RMSE) to assess the models' performance.

## Results
We found that all the models showed high error rates, and not scaling the data resulted in better performance. We also discovered that reducing the number of training features initially improved performance, but further reduction had only a marginal effect. After considering all factors, we chose to use 40 features in our final model.

## Conclusion
Our analysis highlights the importance of accurate delivery time predictions for a positive consumer experience. While we could not achieve optimal results with our models, we have identified some factors that can improve performance. Further improvements could be achieved by incorporating additional features or exploring alternative models.

## Author
