# SC1015 W132 Group 2 Project: Analysis of Earthquake Characteristics and Predictive Factors for Magnitude

### Earthquake Data from Kaggle 
https://www.kaggle.com/datasets/warcoder/earthquake-dataset

Data is under CC0: Public Domain which allows our group to freely build upon, enhance and reuse the works for any purposes without restriction under copyright or database law.

Our data analysis mainly includes steps of data selection, visualization and multivariate modeling. In data selection, we remove some variables that are not related to earthquake magnitude and location, and keep only key data. In visualization and multivariate modeling, we divide the Richter magnitude into three categories and try to predict more accurate earthquake magnitude by DecisionTree, SVM, and Randomforest. Through these steps, we draw some conclusions about the correlation between seismic variables and earthquake magnitude and can infer the earthquake magnitude by considering factors such as earthquake damage index and latitude and longitude of the earthquake occurrence.

Translated with www.DeepL.com/Translator (free version)
### Datasets info
title: title name given to the earthquake.

magnitude: The magnitude of the earthquake

date_time: date and time

cdi: The maximum reported intensity for the event range

mmi: The maximum estimated instrumental intensity for the event

alert: The alert level - “green”, “yellow”, “orange”, and “red”

tsunami: "1" for events in oceanic regions and "0" otherwise

sig: A number describing how significant the event is. Larger numbers indicate a more significant event.

latitude / longitude: coordinate system by means of which the position or location of any place on Earth's surface can be determined and described

We used 782 earthquake data which has Richter magnitude >=6.5 from 2001/1/1 to 2023/1/1.
