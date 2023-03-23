# Weather-Prediction-Using-Big-Data
### CSE3025- Large Scale Data Processing Project 

---
#### OUTCOMES:

* To find out the maximum and minimum temperature of the city for a 
year from map-reduce.
* To analyze the weather data to find out the precipitation levels and 
amount of rainfall for a year.
* To predict the probability weather conditions using the simple Naïves 
Bayesian classification method.
* To provide visualization of the data and compare the rainfall and 
precipitation levels.

---
TOOLS USED:
* Java Open-JDK-7 
* Hadoop Tool 2.7.1
* PyCharm
---

#### IMPLEMENTATION
* *To find the hottest, coldest day from the data depending on temperature and comparing precipitation levels to find whether a particular day received light, moderate or heavy rains using Map-Reduce Programming*
  * Download the weather_data.txt dataset from Data folder and MyMaxMin.java file.
  * Open Eclipse software and open the java file. Build the path by configuring it and adding the necessary external jar file libraries in the classpath of the program.
  * Export the temperature.jar file from the main class of the program and store it in the system.
  * Now in the terminal, give the commands start-dfs.sh and start-yarn.sh to initiate Hadoop in the system.
  * Open the localhost page and browse through file system.
  * Copy the weather dataset file into HDFS using the hdfs dfs –put command.
  * Run the jar file by giving hadoop jar temperature.jar MyMaxMin.
  * Once the program runs successfully, browse the file system and go to the output file. Now download the part-r-00000 file from HDFS which contains the output.

* *Naïve Bayesian Classifier Implementation for Weather Prediction*
  * Download the new_dataset.csv from Data folder and simplenaivebayes.py file.
  * Execute the python file to find probabilities using the Naive Bayes classifier.
* *Rainfall Prediction Using Linear Regression Model*
  * Download the weather.csv dataset from Data and main.py file.
  * Execute the python file to find rainfall prediction using the linear regression model.
