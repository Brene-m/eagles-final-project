# CALL VOLUME PREDICTION USING TIME SERIES.

![image](https://user-images.githubusercontent.com/22292343/191199685-51b097dc-2c9b-405a-92cc-48ae9eb57381.png)

#### LINKS

#### link to the data

https://zindi.africa/competitions/mtoto-news-childline-kenya-call-volume-prediction-challenge/data

#### link to the notebook

https://colab.research.google.com/drive/1ZYQjiZZLxWt7O3WRsf05f9KQyBf4l7uT#scrollTo=1aENy5weXUIe

#### OVERVIEW OF THE PROJECT

It is vital for the society as a whole to protect children. Although this is what is expected, over the years there has been an increase in cases of child abuse . This has steered the need for quick and prompt response to facilitate the rescue process of the children.

Mtoto News a company that ensures the well being of children through technological incorporation to facilitate the rescue process has approached us for help in making a model that would enable them forecast the number of calls that they are bound to receive on an hourly basis.

With this model , Mtoto News stakeholders believe that they will be in a posititon to allocate resources efficiently, know the days they receive most calls, have an insight on the months with the highest cases of abuse but most importantly have knowledge about the number of calls daily.

#### Data:

The original data was obtained from the zindi africa .

The data has 4 files WeatherNairobi2016, NairobiSchoolDates2016, KenyaPublicHolidays2016 and train2016.



#### Steps:

Understanding Data

Cleaning and Exploring Data

Preprocessing Data

Building auto-arima model


#### Metric of success: 

The evaluation metric for thsi project is the Root mean squared error. 
The metric helps us evaluate how well the model predicts the calls versus the actual calls that are made.


#### MODEL CONCLUSION AND RECOMMENDATION

#### Conclusions
## EDA
Most calls were made by adults
Nairobi county reported the most cases of child abuse
Most cases of child abuse were reported during the month of July
Most calls on abuse were made at 11am
Fathers were reported to be the major abusers
Females were the most abused while males reported the most cases
## Modelling
There's a rising trend in the call volume.
The impact of holidays on the call volume is clearly visible
Tuesday and Thursday were the busy days for Childline Kenya in terms of call volume.
The number of calls peaked between 10am and 4pm

#### Recommendations
The peak days are: Tuesdays and Thursdays. Due to the overwhelming number of calls, blank calls are recorded. For this reason the Childline kenya should increase the number of call agents to handle number of blank calls especially on peak days.(blank calls-these are calls not picked by the agents or are picked but not responded to).
The Childline should visit schools to create awareness of child abuse by holding conferences to teach and remind the students of safety measures to take just before the students go for holidays and immediately when they return.
The Childline needs to train staff on how to engage silent calls as the caller might be a child.
Childline Kenya needs to sensitize children by carrying out teachings in schools and churches on how to relate with adults as most of the abusers happen to be people most closest to them



