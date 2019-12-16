How to start the project

Create a HousePrices folder

Inside this folder clone this repository : 
```
git clone https://github.com/Simplon-IA-Bdx-1/house-prices-christophe-maxime.git
```

Create an Anaconda environment :

    conda env create -f environment.yml

Here below is a description of each script in the repository :

1 - Data Analysis with R.ipynb :
- PCA 
- Correlation matrix
- Data visualization
with R

2 - Data Exploration & Data Set Cleaning.ipynb :
- Data visualization with Seaborn library
- Outliers cleaning
- Missing values replacement
- Qualitative feature transformation to quantitative features.

3 - House Prices XGBRegressor.ipynb : 
- added linear regression with xgboost

4 - HousePrices_Keras_full_quanti.ipynb : 
- Quantitatives features selection
- Missing values replacement
- Features standardization
- Keras Sequential Model with MSE loss function

5 - HousePrices_Keras_quanti_to_kaggle.ipynb :
- added Quantitatives features selection
- Keras Sequential Model with MSE loss fuction
- Kaggle submission

6 - HousePrices_Keras_quanti_et_quali_to_kaggle.ipynb :
- added qualitatives features transformed to quantitatives features
- Keras Sequential Model with MSE loss fuction
- Kaggle submission

7 - Linear-Regression-House-Prices-1D-Keras.ipynb :
- Keras Sequential Model with MSE loss function on one quantitative feature