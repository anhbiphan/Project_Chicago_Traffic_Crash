# Mod-3-Traffic-Crash-Project


# Chicago Traffic-Crash Data Link:
https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

## Project Presentation:
https://www.canva.com/design/DAD5dJB86ec/DoQp3RyGoAhzPcNNPxh7qg/view?utm_content=DAD5dJB86ec&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink

### Project Details:
Data Source: Based on Chicago Police Department Crash Dataset. 
Data Breakdown: Dataset describes traffic crash parameters, including date of crashes, street name, weather condition, posted speed limit, traffic way type, types of road defects etc. 


#### Goals  
- Create a model that predicted and classified types of traffic crashes. Also to predict if the traffic crashes was going to be a "Rear End" crash or not. Dataset parameters were used to predict and distinguish between types of crashes such as "Rear End". 

#### Problems:
- LabelEncoding, OneHotEncoding and merging dataframes to obtian a cummulative dataset that had everything we needed.
- Losing data after merging or adding columns. 
- Large amounts of 'Unkown' and NaNs.
#### Solutions:
- Effective Googling for assistance.
- Experiementing with the code to check if they worked correctly. 
#### Recommendations for further developments:
- Grab Vehicle Dataset and Driver/Passenger Dataset. Combining them with our Traffic Crash dataset. 
- Binning and Clustering data in the future to find location of crashes.
- Improve model.

## Project Intro/Objective
- We wanted to find out if a crash was a "Rear End" crash or not. So classifying this would require us to use DecisionTreeClassifier and RandomForestClassifer models to distinguish between the two. 
      
      'TRAFFIC_CONTROL_DEVICE',
      'DEVICE_CONDITION', 
      'WEATHER_CONDITION', 
      'LIGHTING_CONDITION',
      'TRAFFICWAY_TYPE', 
      'ALIGNMENT', 
      'ROADWAY_SURFACE_COND', 
      'ROAD_DEFECT',
      'INTERSECTION_RELATED_I', 
      'NOT_RIGHT_OF_WAY_I', 
      'HIT_AND_RUN_I',
      'PRIM_CONTRIBUTORY_CAUSE', 
      'SEC_CONTRIBUTORY_CAUSE', 
      'DOORING_I',
      'WORK_ZONE_I', 
      'WORK_ZONE_TYPE'
  
## Project Findings:
- The most important feature that played a big role in classifying was 'PRIM_CONTRIBUTORY_CAUSE'.

       'UNABLE TO DETERMINE', 'FAILING TO YIELD RIGHT-OF-WAY',
       'FOLLOWING TOO CLOSELY', 'NOT APPLICABLE',
       'IMPROPER OVERTAKING/PASSING', 'IMPROPER BACKING',
       'FAILING TO REDUCE SPEED TO AVOID CRASH', 'IMPROPER LANE USAGE',
       'IMPROPER TURNING/NO SIGNAL', 'DRIVING SKILLS/KNOWLEDGE/EXPERIENCE',
       'WEATHER', 'DISREGARDING TRAFFIC SIGNALS',
       etc.

### Methods Used
* Statistics
* Data Cleaning
* Data Organizing/Exploring
* LabelEncoding, OneHotEncoding
* Feature Engineering
* Machine Learning
* Data Visualization
* Predictive Modeling
* GridSearchCV
* export Graphviz

### Metrics Used:
- accuracy_score : We wanted to test how accurate our model's predictions are.
- roc_auc_score : We wanted a metric that shows to well the model distingushes between two classes. 

## Models Used:
- DecisionTreeClassifer : Based on 1 tree, we wanted to identify where the splits were being made.
- RandomForestClassifer : We used RandomForest to see if the model can become more accurate and better at predicting classes if it was given more trees to split on. 
    
### Technologies
* Python
* Pandas, Jupyter
* Seaborn
* Matplotlib
* Numpy
* Scikit learn


## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- car crash indentifying
- parameters that may lead up to a crash
- exploring locations of crash
- understanding hour/day/month of majority crashes


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if
    
3. CarCrashData.ipynb and Traffic_Crash-Anh.ipynb will contain data cleaning, findings, and visuals. 
4. mytree.png will contain visual of DecisionTreeClassifier split parameters.



#### Project Members:

|Name     |  Github   | 
|---------|-----------------|
|
|[Anh Phan](https://github.com/anhbiphan)
|[Jesus Fuerte](https://github.com/jesus12279)


