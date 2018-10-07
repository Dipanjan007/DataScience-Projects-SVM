# DataScience-Projects-SVM-Predicting-Cancer

## Predicting Cancer using various Medical parameters

**NOTE** Be careful with moving back and forth the various sections in this assignment as we will be building a lot of models and unexpected things might happen if you don't carefully handle the objects in your global environment

## Agenda 

* Read in the data

* Data Pre-processing

* Build a linear SVM model

* Do cross validation for finding the optimal C value

* Build SVM with Kernels

* Report Metrics of the various Models on Test Data

# Reading & Understanding the Data

* Read in the .csv file
The dataset has 569 observations with 32 variables, the descriptions of the variables are given below :

1) **id** : Unique identification number of the sample

2) **Cancer** : This column represents whether the patient has a benign/normal tumor (0) or a cancerous one ("1")

3) **The remaining 30 variables** are real valued measurements some of which are given below:

	* radius (mean of distances from center to points on the perimeter)
	* texture (standard deviation of gray-scale values)
	* perimeter
	* area
	* smoothness (local variation in radius lengths)
	* compactness (perimeter^2 / area - 1.0)
	* concavity (severity of concave portions of the contour)
	* concave points (number of concave portions of the contour)
	* symmetry 
	* fractal dimension ("coastline approximation" - 1)
