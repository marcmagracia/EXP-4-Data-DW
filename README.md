# Experiment 4: Data Wrangling and Data Visualization

_This is the fourth of several repositories I will upload to document my progress in Python programming through several exercises I am and will be performing. In this project, I am expected to to apply and use the different codes and functions in creating a Python program that will be used in data wrangling and data visualization_

## | Description/Given Problems
_Download the ECE Board Exam 2 dataset and write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin._

#### ECE BOARD EXAM PROBLEM: 
Using data wrangling and data visualization technique with storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given. 

1.] Create the following data frames based on the format provided: 

_Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas_ 

      Output: 
      -      Name      Gender         Track               Math
      -      S4         Male     Instrumentation           65
      -      S11       Female     Communication            48
      -      22        Female     Communication            64

- Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as 
Instrumentation and hometown Luzon 
- Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female 

2.] Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score? 

## | Getting Started

### Dependencies
* Anaconda Navigator ver. 2.6.0 or later
* Jupyter Notebook ver. 7.0.8 or later
* Any form of OS (Windows/Mac) that supports running the above software and Python code

### Supplementary File
* 'board2.csv' - Dataset to be used in the program

### Program Execution
* To successfully run both program files, select a specific cell and press Shift + Enter.

_1.] Create the following data frames based on the format provided:_
* To use the Pandas library, it must be imported in both codes using 'import pandas as pd'.
* To use the Matplotlib, it must be imported in both codes using 'import matplotlib.pyplot as plt'.

_2.] Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?_
* Upon visualizing the data, here are the implications that can be observed:
  * The highest average score was obtained by a female.
  * The highest average score was by a Microelectronics track, but the mean score of Communication students are the highest.
  * The average score of all the takers from Luzon are the highest, and the ones from Visayas are the lowest.


## | Author
_Magracia, Marc Reggie Sean S. | 2ECE-C_

## | Version History
* v1.2
  * Corrected comments in the .ipynb file
* v1.1
  * Updated README and uploaded supplementary files         
* v1.0 (17 September 2024)
  * Created 
