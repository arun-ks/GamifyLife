# Gamify Your Life

This excel based tool gamifies your life using logs of your activities. The idea is to use the techniques used in video/arcade games to help people motivate and to track progress.

You can assign +ive points for good habits/behavior & -ive for bad ones. 

![alt text](https://github.com/arun-ks/GamifyLife/blob/master/help/Instruction03.jpg "Summary View")

## How does it work

> "Your actions become your habits"

Each activity is associated with some points (+ive for good things, -ive for bad ones). As you log activities, the excel will calculate your health-status. 


## Initial Setup 
1. Download **GamifyLife.xlsm** excel 
2. Add activities in the worksheet "LoggerMaster" of the excel
  1. Add the activities you want to track in cells A2:A13
  2. In cells B2:B13 insert the points you want to give/take for them. Give +ive values for **good** habits & -ive for **bad** ones
  3. In cells L18 & L19 add the maximum point you can take & your health.

![alt text](https://github.com/arun-ks/GamifyLife/blob/master/help/Instruction01.jpg "Setup Habits")

## Logging Data
On the worksheet "LoggerMaster", use the Button "Log an Activity", press submit when done.
![alt text](https://github.com/arun-ks/GamifyLife/blob/master/help/Instruction02.jpg "Logging an Activity")

Notice that some of the activities allow you to add **numeric** metrics (for example, the count of your situps).

You can also manually add a entry in the "LoggerData" worksheet (take care of formula used there). In this case, you need to press the "Recalculate" button on "LoggerMaster" to update the counters 

## Summary Tracking view
On "LoggerMaster" you can see the Score for each activity, the Iterations(number of times you did it), the last Date, the max-minimum values if applicable (this works only for numeric metrics) & the number of days since you last did the activity.

![alt text](https://github.com/arun-ks/GamifyLife/blob/master/help/Instruction03.jpg "Summary View")

On lower right had side, you can see the **health**

## Pivot table for some habits
You can customize pivot table on "LoggerGraph" worksheet to track progress of Activities which include some metric.
![alt text](https://github.com/arun-ks/GamifyLife/blob/master/help/Instruction04.jpg "Pivot Graph")

## Known issues 
For activities which do not have any metrics, the excel uses 99 as a filler value - this is done to make the pivot graph look nice.
So, if the metric for your task has the value "99", it will cause issues.

## Files in the package
1. "GamifyLife.xlsm" : The file you can use to track your life. This is the only stuff you need.
2. "GamifyLifeSample.xlsm" : A used example filled with dummy data for you to check how this works.
3. "help" folder : Images used in this readme.

