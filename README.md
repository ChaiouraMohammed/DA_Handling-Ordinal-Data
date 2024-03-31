# DA_Handling-Ordinal-Data
Ordinal data is a categorical, statistical data type where the variables have natural and ordered categories.

## Exemple for Ordinal data
![image](https://github.com/ChaiouraMohammed/DA_Handling-Ordinal-Data/assets/91562298/2a8b08a1-0588-4c88-a1df-57592769f362)

## So how can we handle this kind of data ?
OKee, interessant , ich schlage vor, das Scikit-Learn zu benutzen. 

```
from sklearn.preprocessing import OrdinalEncoder
```

## dataset 
```
d = {'sales': [100000,222000,1000000,522000,111111,222222,1111111,20000,75000,90000,1000000,10000],
      'city': ['Tampa','Tampa','Orlando','Jacksonville','Miami','Jacksonville','Miami','Miami','Orlando','Orlando','Orlando','Orlando'],
      'size': ['Small', 'Medium','Large','Large','Small','Medium','Large','Small','Medium','Medium','Medium','Small',]}
```
![image](https://github.com/ChaiouraMohammed/DA_Handling-Ordinal-Data/assets/91562298/03b17fbe-02b4-4edd-b775-7efd36483fe8)

## Final OutCome 
![image](https://github.com/ChaiouraMohammed/DA_Handling-Ordinal-Data/assets/91562298/027e882a-8b54-4849-b9ec-e9f83208bc62)

