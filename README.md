# Water-Well-Project

### Problem Description
Tanzania has a shortage of clean water that can be provided to its people. The population of Tanzania is about 56 million and about 4 million citizens do not have access to clean water.

The goal of this project is to create a model that can accurately predict if a well is functional or not. This model can then be used to help improve maintenance operations all across Tanzania.

### Data and packages
The raw data was provided through a Driven Data Competition by Taarifa and the Tanzanian Ministry of Water.

Packages used
- sklearn
- imblearn
- xgboost

Snapshot of Raw Data
- 59,400 wells
- 40 features
  - 6 continuous
  - 34 categorical
- Target variables
  - functional (32,259)
  - non functional (22,824)
  - functional needs repair (4,317)

### After EDA
- 57,588 wells
- 27 features
  - 6 continuous
  - 21 categorical
- 1,236 features after creating dummy variables

### Map of markers/group markers of the types of wells
Group markers of functional wells

<img src="https://github.com/stevenkyle2013/Water-Well-Project/blob/main/Pictures/FunctionalGroupMarker.png" width="500">


Group markers of wells that need repair
<img src="https://github.com/stevenkyle2013/Water-Well-Project/blob/main/Pictures/NeedsRepairGroupMarker.png" width="500">

Group markers of nonfunctional wells
<img src="https://github.com/stevenkyle2013/Water-Well-Project/blob/main/Pictures/NonFunctionalGroupMarker.png" width="500">


### Final Model used
Random Forest

<img src="https://github.com/stevenkyle2013/Water-Well-Project/blob/main/Pictures/FinalModel.png" width="500">

0 indicates functional
1 indicates functional needs repair
2 indicates nonfunctional

### Summary and future work
The most effective model that was used was Random Forest. The final model had an accuracy of 80.5% and was able to recall functional wells by 89% and nonfunctional wells by 77%.

I would like to do some more EDA on this project to improve the model. Since Hyper-parameter tuning did not affect the model that much, I believe the best way to improve the model is to do some more data pre-processing.
