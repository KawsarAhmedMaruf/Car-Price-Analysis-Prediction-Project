**Car Price Prediction Project**

This Car Price Prediction project aims to predict the selling price of used cars based on various features such as the current price, kilometers driven, fuel type, seller type, transmission, owner history, and number of years since the car was bought.

The project starts with data exploration and preprocessing using the pandas library. The dataset is loaded from a CSV file and unnecessary columns are dropped. The categorical variables are encoded using label encoding for further analysis.

Several visualizations are created using seaborn and matplotlib libraries to gain insights into the dataset. The average selling price is analyzed based on fuel type, seller type, transmission, and owner type. These visualizations provide a comprehensive understanding of the influence of these features on the selling price.

Next, the dataset is split into training and testing sets for model development. The project compares the performance of three different regression models: Linear Regression, Random Forest Regressor, and XGBRegressor. Evaluation metrics such as R2 score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) are calculated for each model. Additionally, the XGBRegressor model is fine-tuned using hyperparameter optimization with a grid search.

The best-performing model is the XGBRegressor with hyperparameter tuning, which achieves an R2 score of 0.8628, an MAE of 0.876, an MSE of 3.5366, and an RMSE of 1.8806.

In conclusion, this Car Price Prediction project demonstrates the effectiveness of machine learning algorithms in predicting the selling price of used cars. The XGBRegressor model with optimized hyperparameters provides the most accurate predictions. This project can be used by car buyers, sellers, and dealers to estimate the fair price of a used car based on its characteristics.
