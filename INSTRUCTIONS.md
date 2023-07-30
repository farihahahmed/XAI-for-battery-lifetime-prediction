# How to use instructions

**Load Data.ipynb** can be used to convert the raw data into usable file formats. For raw data, see https://www.nature.com/articles/s41560-019-0356-8.

**BuildPkl files**: used to make pickle dumps of the three batches of cells

**For processed data:** See the two CSV files normalized_discharge_app1.csv and normalized_fullmodel_app1.csv. Both data sets are normalized and ready to use in the ML files (see below more details on the ML files). The discharge model and full model data sets can be used as is, and for the variance it needs to be derived (but this is already done in the ML files). 

**Regular files:** The files are formatted in the following way: **number of cells-train %-test %**. For instance, 100-50-50.ipynb means in this file, we tested 100 cells with 50-50 on train and test.

**Hyperparameter tuning files:** same files as above, but they begin with PARAMS. Hyperparameter tuning done here, found best results here.

Many here are experimental files, such as the files beginning with 'outliers' (we took out the outliers to see the impact on results).

