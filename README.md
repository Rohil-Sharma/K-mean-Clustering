
# K Mean Clustering 

K Mean Clustering of Customer depending on their salary ($) & Expenditure($)



## 🚀 About Me
I'm an Anspiring Data Analyst. Who is trying to learn new things on routine basis.

  
# Hi, I'm Rohil Sharma! 👋
I started working on Data in 2019 but come in contact with Big Data in 2020.
Now trying to learn More in the same and gathering the information regarding the same
  
## 🔗 Links

[![linkedin](https://www.linkedin.com/in/rohil-sharma/)
[![twitter](https://twitter.com/rohil_sharma)

  
## Acknowledgements

 - [Data Set Downloaded from](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
  
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`Python3`

`Jupiter Notebook`

  
## Documentation

[Task To Perform](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python/tasks)

  1. Find the hidden spending patterns
  2. The specific characteristics of target group


You've probably managed to verify which group of mall customers is the main target - firstly, these are people whose both annual income and spending score are high. Secondly, it might also be the group of people who don't earn much, but they are eager to spend a lot of money (maybe they are easily influenced by commercials and special offers?).

Task Details
Try to describe the target group as precisely as possible to be able to present the most efficient marketing strategy:

gender
age
income
## Installation

Install my-project with Python Libraries like Numpy, pandas 

```bash
#import the libraries
import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
import matplotlib.pyplot as plt #Data Visualization 
import seaborn as sns  #Python library for Visualization
```
```
#Building the Model
#KMeans Algorithm to decide the optimum cluster number , KMeans++ using Elbow Mmethod
#to figure out K for KMeans, I will use ELBOW Method on KMEANS++ Calculation
from sklearn.cluster import KMeans
wcss=[]
```
    