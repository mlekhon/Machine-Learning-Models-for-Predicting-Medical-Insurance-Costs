Model Comparison for Predicting Medical Insurance Charges Using Machine Learning 
# Abstract
This study compares the performance of three regression models—Linear Regression, Decision Tree Regressor, and Random Forest Regressor—applied to a dataset containing medical insurance charges and individual attributes. The goal is to identify the model that provides the most accurate predictions while minimizing overfitting. Through cross-validation and evaluation using Mean Squared Error, the Linear Regression model emerges as the most precise predictor among the tested models. This research highlights the significance of model selection and its impact on predicting medical insurance charges based on diverse factors.
# Introduction 
In the realm of healthcare economics, accurately predicting medical insurance charges plays a pivotal role in risk assessment, pricing strategies, and resource allocation. This study delves into the comparative analysis of three distinct regression models—Linear Regression, Decision Tree Regressor, and Random Forest Regressor—to ascertain their effectiveness in forecasting insurance charges based on a multifaceted set of individual attributes. By examining their predictive performance and considering the intricacies of model complexity, this research aims to contribute valuable insights into the selection of optimal predictive algorithms for this critical domain.
# Dataset
The dataset used for this analysis contains information about insurance charges along with individual attributes such as age, sex, BMI, children, smoking status, and region. The dataset was preprocessed to convert categorical variables into numerical values using one-hot encoding.
# Methodology
We performed cross-validation with 5 folds to consistently assess the models' performance across different data splits. The evaluation metric used was the Mean Squared Error (MSE), which measures the average squared difference between predicted and actual charges. Lower MSE values indicate better predictive performance.
# Results
The following table summarizes the average MSE values obtained for each model:

| Model | Average MSE |
| -------- | -------- |
| Linear Regression | 36538822.43 |
| Decision Tree | 44048917.52 |
| Random Forest | 23301354.34 |

# Model Comparison Visualization
Box Plot Comparison
The box plot visualization above displays the distribution of MSE scores for each model. The "Random Forest" model exhibits the lowest median MSE, followed by the "Linear Regression" model, while the "Decision Tree" model has the highest median MSE. The box plot also highlights the spread and potential outliers of MSE scores for each model.
# Conclusion
In the pursuit of precise medical insurance charge predictions, this study systematically evaluated and compared three regression models. Through rigorous cross-validation and assessment of Mean Squared Error, our analysis reveals that the Random Forest model outperforms the Decision Tree and Linear Regression models regarding accuracy and generalizability. The findings underscore the significance of tailored model selection, shedding light on the potential for leveraging simple yet robust algorithms to enhance predictive capabilities in healthcare insurance settings. As the demand for accurate risk assessment and cost estimation continues to grow, this research offers valuable guidance for refining predictive modeling strategies in the healthcare industry.
