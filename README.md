# **Predicting Home Prices with Regression**

## **Goal:**
The project aims to predict the prices of homes using *regression techniques*, evaluating the model's performance based on **R2** and **RMSE** metrics. The goal is to create a reliable model that **minimizes the deviation between predicted and actual home prices**.

## **Overview:**
In this machine learning journey, I explored regression to predict home prices, moving beyond a binary classification whether a home is expensive or not. The focus shifted to evaluating the model's ability to approximate actual home values. I experimented with **different models, hyperparameter tuning, feature selection, and preprocessing techniques** to enhance predictive accuracy.

## **Approach:**
1. **Baseline Model:** Implemented a *DecisionTreeRegressor* with *RandomSearch* hyperparameter tuning as a baseline, achieving an initial R2 of 0.79.
2. **Troubleshooting:** Explored options for improvement, including revisiting preprocessing choices and experimenting with more robust scalers, imputers, and models.
3. **Feature Importances:** Utilized *LazyPredict* to identify top-performing models and aggregated their feature importances. Explored the impact of removing features with less than 1% predictive power.
4. **Data Exploration:** Analyzed missing values, data types, scale, skewness, and correlation of features. Explored the significance of remaining features.
5. **Transforming, Scaling, and Imputing:** Implemented a *LogTransformer*, *MinMaxScaler*, and *KNN imputer* to enhance the model's ability to handle diverse numerical features.
6. **Final Model:** Employed a *VotingRegressor* on the top predictive features identified by the ensemble of models, achieving a final R2 of close to 0.95.

## **Deliverables:**
The project includes a **Google Colab notebook** containing the code for the regression analysis [here](https://github.com/Cintia0528/Project-8-Supervised-Machine-Learning-Regression/blob/ab4134a446ae810915e383f547aa33ae935c2efa/2_b_Housing_Feature_Selection.ipynb). The findings and methodology are further explained in a detailed **Medium article** [here](https://medium.com/@ubp0528/how-close-can-i-get-to-your-homes-true-value-with-regression-4e708ba1662f).

## **Skills and Tools:**
- Regression modeling
- Hyperparameter tuning
- Feature Engineering
- Data Exploration
- Preprocessing
- Python
- scikit-learn
- XGBoost
- LightGBM
- LazyPredict

## **Further Analysis:**
To enhance the model's performance:
- **Feature Engineering:** Continue exploring feature engineering techniques to create new meaningful features.
- **Ensemble Techniques:** Experiment with different ensemble models or stacking approaches to leverage the strengths of multiple models.
- **Advanced Hyperparameter Tuning:** Explore more advanced hyperparameter tuning techniques to fine-tune model parameters for better performance.
- **External Data:** Consider incorporating external datasets to provide additional information and improve predictive accuracy.

By focusing on these areas, the model's **R2** score and **RMSE** could potentially be further improved, providing more accurate predictions of home prices.
