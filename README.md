# Titanic Survival Prediction


## Imported all the required library
```
import pandas as pd
import numpy as np
from sklearn.cross_validation import train_test_split
from sklearn.neighbors import KNeighborsClassifier
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier

```
### Loading and Viewing the data

~~~
data=pd.read_csv('titanic_data.csv')
data.head()
~~~

### Pltoting the survival rate
![alt welcome](https://github.com/Titanic-Survival-Prediction/blob/master/screen_shots/survived_people.png)
