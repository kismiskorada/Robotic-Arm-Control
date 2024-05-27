# Robotic-Arm-Control
In this project, I developed a machine learning approach to predict the angles of a robotic arm's joints based on the end-effector's position. The methods involved linear regression and K-Nearest Neighbors (KNN).

Data Preparation:
The dataset contained joint angles and corresponding end-effector positions. I split this data into training and testing sets after careful inspection.

Model Training and Normalization: 
I used a MinMaxScaler to normalize the features, ensuring consistent scaling between training and testing data.

Model Implementation:

Linear Regression: Using Ridge regression, I trained the model with regularization on scaled training data, predicting joint angles for the test set.
KNN Regressor: I selected a suitable number of neighbors for the KNN model, trained it similarly, and made predictions.

Performance Evaluation:

Metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² Score were calculated for both models.
Comparative Analysis: KNN outperformed linear regression, showing lower MSE, RMSE, and MAE, and a higher R² Score, indicating more accurate predictions.

Conclusion:
For tasks such as inverse kinematics in robotics, where precision is vital, the KNN algorithm proved more effective. Further parameter tuning could enhance these results.

This project highlighted the practical utility of machine learning algorithms in robotics, demonstrating their effectiveness in real-world applications.

