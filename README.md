# Germany Rent Predictor

A model using linear regression to predict the rent in Germany from kaggle data. 

## Model

The dataset obtained from kaggle had almost 45 columns. But the most relavent columns were the region where the apartment is located and
the area in square meter available. The areas currently supported are :

* Schleswig Holstein 
* Berlin
* Bayern
* Brandenburg
* Sachsen
* Sachsen Anhalt
* Nordrhein Westfalen
* Mecklenburg Vorpommern
* Hamburg
* Rheinland Pfalz
* Hessen

Initially, only relationship between the area and rent was explored. But that model did not perform well. The the region was also integrated.

## Applications

Do you think the rent you are paying is reasonable? Input the amenities of your residential and the model will calculate the
expected rent based on listings. 
