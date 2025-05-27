------------------------------------------------------------------------------------------------------------
APPLICATION 2
------------------------------------------------------------------------------------------------------------

Description: 
This application deals with analyzing the comparitive analysis of all feature ranking mechanims
namely SP and WFI as well as all feature selection algorithms namely SPFS and FFS. These 
approaches have been applied on the gas pipeline dataset clusters described below. 

Datatset:
Gas Pipeline dataset clusters namely:
1. NewGasFilteredCommand
2. NewGasFilteredFunction
3. NewGasFilteredResponse

Note:
Files like "Stat_RF_Normalized_5.2.csv" contains the ranking acquired using SP for normalized 
datasets, "WFI_RF_NN_5.2.csv" contain the ranking acquired using WFI for normalized datasets
and so on.

Files:
1. FFS_AllRM_AllNNDatasets.ipynb: Application of FFS with SP and WFI on all non normalized datasets.
2. FFS_SPXGB_AllDatasets.ipynb: Application of FFS with SP using XGB classifier on all datasets.
3. SPFS_AllRM_AllNNDatasets.ipynb: Application of SPFS with SP and WFI on all non normalized datasets.
4. SPFS_SPXGB_AllDatasets.ipynb: Application of SPFS with SP using XGB classifier on all datasets.

Usage:
Open the notebook and run each cell sequentially to:
1. Import necessary libraries.
2. Load and preprocess the dataset (all clusters).
3. Upload the files containing ranked feature sets using SP and WFI. 
4. Train the each model and evaluate its performance by using SPFS and FFS algorithm.
5. Perform 10-fold cross validation

Dependencies:
1. NumPy - For numerical computations
2. Pandas - For data manipulation and analysis
3. Matplotlib - For data visualization
4. Scikit-learn - For machine learning models, evaluation metrics, and data splitting
5. SciPy - For statistical functions (e.g., skewness and kurtosis)
6. XGBoost - For implementing gradient boosting algorithms
7. Tabulate - For displaying data in tabular format

Classifiers used:
Random Forest (RF), Decision Tree (DT), Gradient Boost (GB), and Extreme Gradient Boost (XGB).