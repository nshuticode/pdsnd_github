----HAPPY CODING!!----
US Bikeshare Data Analysis Project

Overview:
In this project, Python is used to explore data related to bike share systems for three major cities in the United States — Chicago, New York City, and Washington.

The source code takes in raw input from the user to create an interactive experience.
According to the input the code will import the data and will provide information by computing descriptive statistics.
Files used:
bikeshare.py

Source used to handle the issue faced:
# https://www.askpython.com/python/python-indentation
# https://www.quora.com/What-is-unexpected-indent-in-python
# https://stackoverflow.com/questions/1024435/how-to-fix-python-indentation

Softwares used:
Python 3, NumPy, and Pandas all installed using Anaconda
A text editor, like Atom.
A terminal application (Git bash).
Installation links for softwares:
Git for windows - for terminal application using Git Bash
Python using Anaconda (latest version for windows)

Links for software tutorials:
Git - Reference
The Python Tutorial
VS Code Documentation
Code explained in Detail:
How the program works:
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:

1) Would you like to see data for Chicago, New York, or Washington?
2) Would you like to filter the data by month, day, or not at all?
3)(If they chose month) Which month - January, February, March, April, May, or June?
4)(If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?

The answers to the questions above determined the city and timeframe on which data analysis done. After filtering the dataset, the statistical result of the data were able to start again or exit.

The Datasets:
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2021-01-01 00:08:00)
End Time (e.g., 2021-01-01 00:07:00)
Trip Duration (in seconds - e.g., 600)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:

Gender
Birth Year
Statistics Computed:
The code helps user to tell about bike share use in Chicago, New York City and Washington by computing a variety of descriptive statistics. In this project, the code output will provide the following information:

Popular times of travel (i.e., occurs most often in the start time):

most common month
most common day of week
most common hour of day

Popular stations and trip:

most common start station
most common end station
most common trip from start to end (i.e., most frequent combination of start station and end station)
Trip duration:

total travel time
average travel time

User info:

counts of each user type
counts of each gender (only available for NYC and Chicago)
earliest, most recent, most common year of birth (only available for NYC and Chicago)

----HAPPY CODING!!----
