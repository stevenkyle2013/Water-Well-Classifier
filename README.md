# Water-Well-Project

### Problem Description
Tanzania has a shortage of clean water that can be provided to its people. The population of Tanzania is about 56 million and about 4 million citizens do not have acess to clean water.

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

### Final Model used
Random Forest
<insert picture of model output>
0 indicates functional
1 indicates functional needs repair
2 indicates nonfunctional

### Summary
The most effective model that was used was Random Forest. It had an accuracy of 79% and was able to recall functional wells at 85% and nonfunctional wells at 78%.
