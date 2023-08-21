About the dataset
-----------------------------------
diabetes _ 012 _ health _ indicators _ BRFSS2015.csv is a clean 
dataset of 253,680 survey responses to the CDC's BRFSS2015. 
The target variable Diabetes_012 has 3 classes. 
0 is for no diabetes or only during pregnancy, 
1 is for prediabetes, and 2 is for diabetes. 
There is class imbalance in this dataset. 
This dataset has 21 feature variables
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset


More information:
https://www.cdc.gov/pcd/issues/2019/19_0109.htm


the order this project was created
-----------------------------------

1 - exploratory_data_analysis.ipynb
2 - feature_engineering.ipynb

3 - model_logistic_regression.ipynb
4 - best_model_eval_logistic_regression.ipynb

5 - model_k_nearest_neighbors.ipynb
6 - best_model_eval_k_nearest_neighbors.ipynb

7 - model_svm.ipynb
8 - best_model_eval_svm.ipynb

9 - model_decision_tree.ipynb
10 - best_model_eval_decision_tree.ipynb

11 - model_random_forest_rus.ipynb (random forest on random undersamping data) 
12 - model_random_forest_ros.ipynb (random forest on random oversampling data)
13 - best_model_eval_rf.ipynb

14 - model_xg_boost_rus.ipynb (xgboost on random undersampling data)
15 - model_xg_boost_ros.ipynb (xgboost on random oversampling data)
16 - best_model_eval_xgboost.ipynb 

17 - best_models_eval.ipynb (FINAL NOTEBOOK)

--- --- --- --- --- 

18 - predict.ipynb 
(a seperate notebook from all notebooks above, where the entire project (a-z) from feature engineering to prediction is included )

--- --- --- --- --- --- --- --- --- ---

PS: [dataset folder / model folder] are empty in order to reduce the size of zip file. 
To produce the datasets and saved model files, (feature_engineering.ipynb) and (best_models_eval.ipynb) must be executed. 

