# Ex03-Univariate-Analysis

# Aim:
To detect the Univariate Analysis by using default functions.

# Algorithm:
1.Import pandas(),numpy()and seaborn() for a required detection.

2.use the head()

3.The information and is null function.

Use the describe function.
5.Figure the boxplot.

6.plot the countrplot,Displot,Histoplot.

7.Print the program.

 #  Program:

 ```

 import pandas as pd
import numpy as np
import seaborn as sns

data=pd.read_csv('SuperStore.csv')
data

data.head()

data.info()

data.describe()

data.isnull().sum()

data.dtypes

data['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=data)

sns.countplot(x='Postal Code',data=data)

sns.distplot(data["Postal Code"])

sns.histplot(x='Postal Code',data=data)

```

# Output

### READFILE
![GITHUB](3ex1.PNG)

### HEAD
![GITHUB](3ex2.PNG)

### INFO
![GITHUB](3ex3.PNG)

### DESCRIBE
![GITHUB](3ex4.PNG)

### ISNULL
![GITHUB](3ex5.PNG)


### DTYPES
![GITHUB](3ex6.PNG)

### COUNT

![GITHUB](3ex7.PNG)

### BOXPLOT

![GITHUB](3ex8.PNG)

### COUNTER PLOT
![GITHUB](3ex9.PNG)

### DISPLOT

![GITHUB](3ex10.PNG)

### HISTPLOT

![GITHUB](3ex11.PNG)

# RESULT

Hence the univariate analyses is verified.




