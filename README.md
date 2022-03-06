
---
### PROJET-4 
### Predictions of energy consumption of the city of Seattle in order to reach its goal of being a carbon neutral city in 2050.
---

<p align="center">
<img align="center" src="support\seattle.png" style="width: 300px" />
</p>

The City of Seattle is looking at the carbon emissions and energy use of non-residential properties by 2050. We will make predictions of 

- **carbon dioxide (CO2) emissions** and
- **total energy consumption** of the city of Seattle 

from existing data.

Our mission is to analyze past data, which was carried out in 2015 and 2016, and to implement Machine Learning algorithms to predict future values that have not yet been measured. Since readings are expensive to obtain, our study was carried out without annual consumption readings.

We will first carry out a short exploratory analysis, test different prediction models in order to best respond to the problem and assess the impact of the EnergyStarScore indicator on the performance of these models. 

Thanks to the Python library **FOLIUM** we have marked the building on a map in [this link.](https://yasarigno.github.io/seattle_folium_map.html) 

---
Data source:

https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv

---

There are 6 notebooks in this project. 

**Notebook 1 :** Data Cleaning. We clean the dataset and perform a first exploratory data analysis. 

**Notebook 2 :** Exploratory Data Analysis.

**Notebook 3 :** Feature Engineering. We transform the raw data into features that more accurately represent the problem underlying the predictive model.

**Notebook 4 :** Machine Learning. We predict carbon dioxide (CO2) emissions using ML models.

**Notebook 5 :** Machine Learning. Prediction of total energy consumptions.

**Notebook 6 :** Machine Learning. We take **EnergyStarScore** into account to see if it increases the performance of the models in Notebook 5.

---
The list of Machine Learning models tested here:
  - Linear Regression
  - Lasso
  - Ridge
  - Elastic Net
  - SVM
  - K Neighbors Regressor
  - Random Forest Regressor
  - Decision Tree Regressor
  - Gradient Boosting Regressor

<p align="center">
<img align="center" src="support\models.png" style="width: 600px" />
</p>

