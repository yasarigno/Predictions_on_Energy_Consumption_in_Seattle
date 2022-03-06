
---
### PROJET-4 
### Building a mobile application for Santé Publique France
---
### Prediction of energy consumption of the city of Seattle in order to reach its goal of being a carbon neutral city in 2050.
<p align="center">
<img align="center" src="support\santepublique.png" style="width: 300px" />
</p>

The [Santé publique France](https://www.santepubliquefrance.fr) has launched a call for projects to find innovative ideas for food-related mobile applications. We propose _*NUTRI + Z*_ that will provide the user:
  - **NutriScore**, which is a letter grade varying from A (best) to E (worst),
  - an alert **Z** which inform the user whether the product likely have adverse effects on health or on the environment. We are working on a dataset which consist of foods or beverages. The alert **Z** takes into account the material of the packaging, the ingredients of the product. For instance, that its package contains plastics will mean that the product may pollute the environment. Therefore, the user will be informed about negative effects of consumpting that product.

We are responsable for verifing if the database of OpenFoodFacts contains enough information to implement the application project. In other words, we provide a result on the feasibility of our project.

Concept of a mobile application 

<p align="center">
<img align="center" src="support\mobile_application_concept.png" style="width: 400px" />
</p>

---
Data source:

https://world.openfoodfacts.org

or

https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip

---

There are 3 notebooks in this project. In the first notebook, we clean the dataset and perform a first exploratory data analysis. We define the related in the second notebook, which are required to built the **Z** alert and ecoscore. There can be found a second data analysis such as correlations between the variables, ANOVA and some statistical tests. 

In the dataset, there exist products for which the variable "NutriScore" is not available. The final notebook provides a way to fill in these missing values. We also see here a good example showing that imputation by mean or median is not always a good idea in the sense that it deforms dramatically the distribution of the target variable, i.e. NutriScore.

---
Technical tools used in this project are
  - Pandas
  - Numpy
  - Math
  - Scipy
  - Seaborn
  - Matplotlib
  - WordCloud
  - KnnImputer
