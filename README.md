# WY Space Java Console Application
## Introduction:
This application:
  * takes the name of the schedule text in comma seperated values form from the user
  * reads this text and uses the data to create Java Objects.
  * takes the bandwidth of ground station
  * calculates the intensity time map of total downLink of all satellites.
  * returns most intensive time interval and total downlink value at this Interval
  * returns that bandwidth of the ground station is enough or not.


## Running the application
* 	Download the zip file
* 	Unzip the zip file
*   Copy your schedule text file or files in the directory "resources"
* 	Open Command Prompt and Change directory (cd) to folder containing pom.xml
* 	Run the Command:```mvn clean package```
    
    This removes the build target before a new build and creates the build result in the target folder.

* 	Run the Command:```mvn exec:java```
    
    Default main class was specified in the plugin's configuration. So this method execute the main method of the          application.

## Used Technologies
This application is created with:
* Java 8
* Maven 4.0.0
* OpenCSV 5.2

## About my scenario and algorithm

* User should put the valid csv file in resources file
* I assume that there is only one time interval in maximum total downlink due to the task description.
* I have used the TreeMap Class for the map of Intensity and Interval. Actually this problem can be solved by using 48 elements (for 30 every minute one element) Integer Array too. But this TreeMap solution is also helpful when our time interval not limited with 30 minute. For Example in "timetest.csv" file i have used total different time schedule to test.
* I have used six different time schedule to test my application in different extension type , in different schedule possibilities and in empty file case.

### Author

Erdem Taskin  
Java Software Entwickler  

**E-mail**: erdemce2234@gmail.com  
**Xing**: https://www.xing.com/profile/Erdem_Taskin3/cv
