# COMP-1012-Assignment-2

Download Here:[COMP 1012 Assignment 2](https://codingherolab.com/product/comp-1012-assignment-2/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Question 1: Required
In this question, you will calculate some statistics for a csv file named reducedweather.csv. The
file contains tabular data which includes Manitoba daily minimum and maximum temperatures
from Jan until Sept 17 in 2019. The first row is a header record (row), with headings Max Temp
and Min Temp. After the header row, each row is a day where maximum and minimum
temperature for that day is recorded. From this file, you need to calculate mean, standard
deviation, highest and lowest temperature for each column.
import time
print (“\nProgrammed by ******YOU******”)
print (“Date: ” + time.ctime())
print (“End of processing”)
The description for this problem is exactly same as the assignment 1 question 1. But here you
need to use functions for reading the file, finding standard deviation, squared difference, max
and mean value.
What to do
Create a module with name StatisticsCalculation. To create the module, you can open a new
python script. Save the script with the given name. The statistics calculation module contains
following functions:
calculateMean(data):
The parameter data is a list of floating point values. Calculate and return the mean. Remember,
data is a single list, it does not contain any nested list.
calculateStdDev(data, mean):
Given a list of data and the mean of the data, calculate and return the standard deviation. Again
remember, data is a single list, it does not contain any nested list. mean is a float value.
findMin(data):
Given a list of data, it will return the min. Data is a single list, it does not contain any nested list.
You can not use any built in function to calculate the minimum value. In this function, you need
to implement your own min function.
findMax(data, mean):
Given a list of data, it will return the max. Data is a single list, it does not contain any nested list.
You can not use any built in function to calculate the maximum value. In this function, you need
to implement your own max function.
Create another module with name InputOutputHandler. This module contains the following
functions:
printCSVResults(headings,means, stdDevs, mins, maxs):
The parameters headings, means, stdDevs, mins and maxs are lists containing the column
headers and statistics from the csv file. You need to print the statistics from this function.
readCSVFile(fileName):
The parameter fileName is a string. Open the file and read the header row and data from the csv
file. Return the header and data. This should be able to read any number of columns from the
csv file.
main():
Create a main function module and from the main function call these functions to find the
statistics. In your main function, there can be several lists to for storing returned minimums,
maximums, standard deviations. To call the functions of StatisticsCalculation module, you need
to import the module. You may call the functions in any order but the result should be exactly
similar to assignment 1 question 1.
Data source: http://climate.weather.gc.ca/climate_data/daily_data_e.html?StationID=27174
Sample output:
Handing in
You must complete the blanket honesty declaration checklist before you can submit your
assignment.
An assignment submission area has been created for Assignment 2. Click on the “Assessments”
menu, then click on “Assignments”.
The only thing you’re required to turn in for this assignment is the .py script that you create.
Please name your script file with the following convention:
Enter file name: reducedweather.csv
Column Names | Mean | Std Deviation | Highest Score | Lowest Score
————–+—————+—————+—————+—————
Max Temp| 10.10| 16.91| 36.60| -29.80
————–+—————+—————+—————+—————
Min Temp| -2.20| 15.17| 21.30| -39.90
————–+—————+—————+—————+—————
