#  Predicting wildfire in California using weather data

California is one of the places having the most deadliest and destructive wildfire seasons. The dataset contains the list of Wildfires that has occurred in California between 2013 and 2020. The dataset contains the location where wildfires have occurred including the County name, latitude and longitude values and also details on when the wildfire has started.

This data helps to generate insights on what locations in California are under fire threat, what time do Wildfires usually occur and how frequent and devastating they are!!

## Getting Started


Collected the weather data based on fire history. Dataset is CSV form and originally includes over 70000 observations. 
Chose the nearest weather location from each fire history data point using Euclidean distance and 
selected 15 days before from the exact fire date. 
Utilized 1 unsupervised model and 2 supervised model: K-means, KNN and Logistics Ression. 
Compared accuracy and error rates of each model and found unsupervised model performed well for predicting the wild fire. 
Selected different variables to increase the accuracy of prediction. 
Used Python to obtain county information and R for data preprocessing and data analysis. 

## 🔑Prerequisites

```
# import packages
import os, glob
import pandas as pd
import numpy as np
import seaborn as sns
import re
import string
import matplotlib.pyplot as plt
import matplotlib.mlab as mlab
import matplotlib
import pickle
plt.style.use('ggplot')
from matplotlib.pyplot import figure

import tweepy
import matplotlib.pyplot as plt
from  textblob import TextBlob 
import time

%matplotlib inline
matplotlib.rcParams['figure.figsize'] = (12,8)

pd.options.mode.chained_assignment = None
```
<!-- ## Installing
## Running the tests
## Break down into end to end tests
## And coding style tests
## Deployment
## 🛠Built With

* [Scikit-learn](https://scikit-learn.org/stable/) 
## Contributing
## Versioning -->
## 💃Authors

* **Preet Mehta**  
<p>
<a href="https://www.linkedin.com/in/preetmehta/">
  <img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/Linkedin%20(1).svg" alt="kushal's linkedin" width="24px" />
</a>  

<a href="https://ynpreetmehta.medium.com/">
<img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/medium-seeklogo.com.svg" alt="Medium" width="25px" height='23.5' />
</a>  
  
<!-- ![Medium](mediumlogo/medium-seeklogo.com.svg?raw=true "Title") -->

 
<a href="https://www.instagram.com/ynpreet/" target="blank">
  <img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/Instagram%20(1).svg" alt="instagram" width="24px" />
</a>

<a href="https://www.youtube.com/channel/UCCcw6HxUkkfrlKn7-6SszDQ/featured" target="blank">
  <img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/youtube-logo-icon-png-svg.png" alt="youtube"  width="25px" height='23.5' />
</a></p><br><br>

## 👀License

This project is licensed under the MIT License - see the [LICENSE.md](https://opensource.org/licenses/MIT) file for details

## 🙏Acknowledgments

* Special Thanks to **[Sisang Cho](https://www.linkedin.com/in/sisang-irene-cho/)** for sharing wonderful insights about Wildfires in California prediction
* [References](https://www.youtube.com/watch?v=1JAhl3b3OFw) 

## 📁 Dataset
You can get the Dataset here

[Link](https://www.kaggle.com/sandstorm0123/wildfires-in-california-prediction/data)

## 💡Working 

Make Sure that you Either Have *Jupyter Notebook* or *Spyder* to Run the code with amazing Visualizations and run any of the following in your Command Prompt in the directory that holds this repo. 

```
Jupyter Notebook
```
or
```
Spyder
```
## 👏And it's done!

- <details> <summary> 💬 Problem Solver. Passion Catalyst. Change Maker. Love simulating conversations especially if done over beer. Feel free to contact in case of any query or to collaborate to work on ML projects😎 </summary> <a href="https://wa.me/919408377842" target="blank"><img align="center" src="https://github.com/ynpreet/Ynpreet/blob/main/images/5ae21cc526c97415d3213554.png" width="40x" /></a>
</details>


