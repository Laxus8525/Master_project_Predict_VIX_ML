# Pyhthon_master_project_Predict_VIX_ML
Apply classification machine learning algorithm to predict the weekly change dirction of vix of us, eurpoe, hk and india.

I selected Decision Tree Classifier, Random Forest Classifier and Extra Trees Classifier from bagging family, AdaBoost Classifier and XGBoost Classifier from boosting
family to investigate which algorithms are the most suitable to make weekly directional volatility index predictions and generating the best strategy returns if we trade on those signals.

For hyper tuning, two-fold time-series cross-validation was used to hyper tune the models to find the best hyper parameters. It starts with a subset of data for training purposes,
and forecasts for the later data points. The forecasted data points are then included as part of the next training dataset and subsequent data points are forecasted, comparing the average accuracy rate of forecasted datasets to output best parameters.
