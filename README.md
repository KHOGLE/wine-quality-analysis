# Wine Quality Analysis

## Group Members
- Jacob Bayer
- Bryson Bosley
- Morgen Henry
- Katharyn Hogle

## Goal
Our main goal for this project is to build a model to estimate the quality of a wine based on a chemical analysis. Our secondary objective is to analyze which qualities of a wine are the most important for predicting overall quality.

## Dataset
Cortez,Paulo, Cerdeira,A., Almeida,F., Matos,T., and Reis,J.. (2009). Wine Quality. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.

## Tools Used
- Python
  - Jupyter Notebooks
  - SKLearn
  - Pandas
  - Tensorflow
  - Keras Tuner
- Tableau

## Results
[Presentation](https://docs.google.com/presentation/d/18nqmfrgjqGF4xc0TjTEjMs5P8dH_pp-TG4lBHklzeTc/edit?usp=sharing)

The most accurate model found was a Random Forest Classifier, giving us a predictive accuracy of .67. We tried many other models, including Neural Networks, with worse results. The most accurate model was used to explore the importance of the induvidual features. The most important features for both Red and White wines were Alchohol and Density, with a Red Wine accuracy of .45 and .41 respectively. White wine predictive accuracy for both of those features was .31. 

In Red Wines, the importance of PH (.27 Red, .12 White) and Sulphates (.36 Red, .11 White) were noteably higher than that of White Wines, while White Wines favored Residual Sugar (.12 Red, .22 White). The remaining Features were relatively equal between Reds and Whites.
