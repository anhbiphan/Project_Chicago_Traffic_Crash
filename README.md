# Chicago-Traffic-Crash-Project


### Chicago Traffic-Crash Data Link:
https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if


### Project Details:
Data Source: Based on Chicago Police Department Crash Dataset. 
Data Breakdown: Dataset describes traffic crash parameters, including date of crashes, street name, weather condition, posted speed limit, traffic way type, types of road defects etc. 


#### Goals  
- Create a model that predicted and classify if a crash is "Rear End" crash or not. Dataset parameters were used to predict and distinguish between types of crashes such as "Rear End". 

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


  
## Project Findings:
- The most important feature that played a big role in classifying was 'PRIM_CONTRIBUTORY_CAUSE'.

       'UNABLE TO DETERMINE', 'FAILING TO YIELD RIGHT-OF-WAY',
       'FOLLOWING TOO CLOSELY', 'NOT APPLICABLE',
       'IMPROPER OVERTAKING/PASSING', 'IMPROPER BACKING',
       'FAILING TO REDUCE SPEED TO AVOID CRASH', 'IMPROPER LANE USAGE',
       'IMPROPER TURNING/NO SIGNAL', 'DRIVING SKILLS/KNOWLEDGE/EXPERIENCE',
       'WEATHER', 'DISREGARDING TRAFFIC SIGNALS',
       etc.

## Models Used:
- DecisionTreeClassifer : Based on 1 tree, we wanted to identify where the splits were being made.
- RandomForestClassifer : We used RandomForest to see if the model can become more accurate and better at predicting classes if it was given more trees to split on. 


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


