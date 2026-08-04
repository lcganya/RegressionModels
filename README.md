# LinearRegression
Regression Model: Temperature Prediction from Humidity
This notebook demonstrates a simple linear regression model to predict 'Temperature (C)' based on 'Humidity' using the Szeged-Weather dataset.

Model Overview
The model is a LinearRegression model from sklearn.linear_model. It's trained on a subset of the weatherHistory.csv dataset, specifically using 'Humidity' as the independent variable (feature) and 'Temperature (C)' as the dependent variable (target).

Key Results
Training Data Fit: The model shows a strong fit to the training data. Visualizations (scatter plot of actual vs. predicted training temperatures) indicate that the predicted values align closely with the actual temperatures, with points clustering well around the regression line.
Test Data Generalization: The model demonstrates good generalization capabilities. When evaluated on unseen test data, the predictions similarly correlate well with the actual temperatures, suggesting the model is not overfitting and performs consistently on new data.
Linear Relationship: The visual analysis confirms a clear linear relationship between humidity and temperature within this dataset, making linear regression an appropriate choice for this problem. While the model performs well, the scatter in the plots suggests that 'Humidity' alone does not account for all variance in 'Temperature (C)', indicating potential for further improvement by incorporating additional features.
How to Run this Notebook on Google Colab
Open in Colab: Click on the "Open in Colab" badge (if added to your README, or manually navigate to Google Colab and upload the .ipynb file).
Run All Cells: Go to the menu bar and select Runtime > Run all. This will execute all the cells in the notebook sequentially.
Interactive Exploration: Feel free to modify the code, experiment with different parameters, or explore other features in the dataset. You can run individual cells by clicking the play button next to them.
This project provides a foundational example of applying linear regression for temperature prediction and visualizing its performance.

