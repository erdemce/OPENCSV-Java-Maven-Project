# WY Space JAVA MAVEN OPENCSV CONSOLE APPLICATION
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

### Author

Erdem Taskin  
Java Software Entwickler  

**E-mail**: erdemce2234@gmail.com  
**Xing**: https://www.xing.com/profile/Erdem_Taskin3/cv
