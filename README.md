# Chicago Crash Dataset

This is an EDA, so I will delve into the data set and identify some useful insights and visualize them

### Data description

CRASH-RECORD-ID             -Unique identifier for the record Number

CRASH-DATE                  -Date and time of crash as entered by the officer Date & Time

POSTED-SPEED-LIMIT          -Posted speed limit Number

TRAFFIC-CONTROL             -DEVICE Traffic control device present at crash location Plain Text

WEATHER                     -CONDITION Weather condition at time of crash Plain Text

LIGHTING                    -CONDITION Light condition at time of crash Plain Text

FIRST-CRASH-TYPE            -Type of first collision in crash Plain Text

TRAFFIC WAY-TYPE            -Traffic way type Plain Text

ROADWAY-SURFACE-COND        -Road surface condition Plain Text

ROAD-DEFECT                 -Road defects Plain Text

CRASH-TYPE                  -A general severity classification for the crash. 

INTERSECTION-RELATED        -A field observation by the police officer whether Plain Text an intersection played a role in the crash. 

NOT-RIGHT-OF-WAY            -Whether the crash begun or first contact was made Plain Text outside of the public right-of-way

HIT-AND-RUN                 -Crash did/did not involve a driver who caused the Number crash and fled the scene without exchanging information 

DAMAGE                      -A field observation of estimated damage. Plain Text

DATE-POLICE-NOTIFIED        -Calendar date on which police were notified of the crash Date & Time

PRIM-CONTRIBUTORY-CAUSE     -Number

NUM-UNITS                   -Number

INJURIES                    -TOTAL Total persons sustaining fatal, incapacitating, non- Number incapacitating, and possible injuries

INJURIES-FATAL              -Total persons sustaining fatal injuries in the crash Number

INJURIES-INCAPACITATING     -Total persons sustaining incapacitating/serious injuries Number in the crash 1

INJURIES-NON-INCAPACITATING -Total persons sustaining non-incapacitating injuries Number in the crash 2

INJURIES-NO-INDICATION      -Total persons sustaining no injuries in the crash Number





### Exploratory data analysis
1. Decide what to do with missing values and extra attributes.
2. Some attributes are more useful if you break them into several attributes. An example of this is already included in the data set where the time, day, and month of the crash are given as separate attributes. These attributes allow you to compare crashes based on the day of the week, time, or month (season). Are there other attributes that you can break down into smaller attributes to gain more information from?
3. What are some insights about the crashes and date/time? You can look into season, day of the week, day/night, lightning, weather, etc.
4. Has number of deadly crashes increased recently? Look at the data over the years. Can you identify any significant increase/decrease?
5. Investigate number and type of injuries based on the speed limit.
6. Is there a relationship between hit and run crashes and number of fatal injuries?
7. Do intersection-related crashes result in more fatal injuries?
8. Interesting insights



### Tech Stack
Python

### Libraries Used
pandas

seaborn

numpy

matplotlib