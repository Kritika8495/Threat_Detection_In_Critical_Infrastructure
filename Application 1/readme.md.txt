------------------------------------------------------------------------------------------------------------
APPLICATION 1
------------------------------------------------------------------------------------------------------------

Description: 
Here, we have used SP feature ranking mechanism and SPFS feature selection algorithm 
in conjunction with various machine learning classifiers on the Gas pipeline dataset to deduce
the best performing models. Also, we have compared the results acquired to results acquired 
from no feature selection and feature ranking. 

Datatset:
The New Gas Pipelined dataset is used here. 

Files:
1. GasPipelineDataset_No_FeatureSelection.ipynb: Contains all classifiers implemented on Gas pipeline dataset without any feature engineering.
2. GasPiplelineDataset_Normalized_Allmodels.ipynb: Contains all classifiers implemented on normalized Gas pipeline dataset with SP-SPFS approach.
3. GasPiplelineDataset_NonNormalized_Allmodels.ipynb: Contains all classifiers implemented on Gas pipeline dataset with SP-SPFS approach.

Usage:
Open the notebook and run each cell sequentially to:
1. Import necessary libraries.
2. Load and preprocess the dataset (New Gas Pipeline Dataset).
3. Apply feature ranking using SP (if applicable).
4. Train the each model and evaluate its performance by using Selective Promising Feature Selection (SPFS) algorithm (if applicable).

Dependencies:
1. Python 3.x
2. NumPy
3. Pandas
4. Scikit-learn
5. SciPy
6. Matplotlib

Classifiers used:
Random Forest (RF), Decision Tree (DT), Gradient Boost (GB), Extreme Gradient Boost (XGB), and Naive Bayes (NB).