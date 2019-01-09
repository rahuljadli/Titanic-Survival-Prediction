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

### Ploting the survival rate

![alt Survived](https://github.com/rahuljadli/Titanic-Survival-Prediction/blob/master/screen_shots/Survival.png)

### Ploting Age graph

![alt Age](https://github.com/rahuljadli/Titanic-Survival-Prediction/blob/master/screen_shots/Age.png)

### Ploting Survival Based on Sex

![alt Sex Survival ](https://github.com/rahuljadli/Titanic-Survival-Prediction/blob/master/screen_shots/Survival_gender.png)

### Ploting Survival Based on Passenger Class

![alt Sex Survival ](https://github.com/rahuljadli/Titanic-Survival-Prediction/blob/master/screen_shots/Survival_Pclass.png)

### Ploting Survival Based on Sibling

![alt Sex Survival ](https://github.com/rahuljadli/Titanic-Survival-Prediction/blob/master/screen_shots/Survival_sibling.png)

### Ploting Survival Based on Parents

![alt Sex Survival ](https://github.com/rahuljadli/Titanic-Survival-Prediction/blob/master/screen_shots/Survival_parch.png)

