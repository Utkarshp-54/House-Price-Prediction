# House Price Prediction Model

## Introduction

This Machine learrning Model is for Prediction of House Price using different Acoustic Paramerters.

### Acoustic Parameters :- 
1) MSSubClass-The building class
2) LotFrontage - Linear feet of street connected to property
3) LotArea- Lot size in square fee.
4)  OverallQual -Overallmaterial and finish quality
5)  WoodDeckSF- Wood deck area in square feet
6)  OpenPorchSF - Open porch area in square feet
7)  FloorSF- Floor square feet
8)  TotalBsmtSF - Total square feet of basement area
9)  SalePrice – total sale price of the house

## Libraries Used :-
1) SK Learn - to Implement model on dataset
2) numpy - 
3) Pandas
4) matplotlib.pyplot

```python
import sklearn
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

## Model Used :-
1) Linear Regression
```python
from sklearn.linear_model import LinearRegression
regressor = LinearRegression()
regressor.fit(x_train,y_train)
```
Here a linear regression is used on the training data set to train the model.

## 
