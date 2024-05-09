# Grade-Calculator
calculates a grade given a dictionary of information


import pandas library

create dictionary function (dataframe):
  - create empty dictionary
  - iterate through each column in dataframe
  - make new key for dictionary with column name and grab list of column to assign as key's value
  - return dictionary

check if score contains numbers (score):
  - list of numbers in string format
  - decimal recorded boolean
  - can be number boolean
  - iterate through string and see if characters is "." or in the valid numbers list
  - check boolean for "." if found once, to make sure it is a valid float
  - if score is not a number, than set can be number boolean to false and break out of loops
  - return can be number boolean

calculate function (dictionary, dataframe):
  - calculate the grades for each section
  - make sure scores are valid numbers by checking to see if the string can be converted to a float (call function)
  - use the calculations from each section to calculate the total grade
  - assign the weights if there is a weighting system
  - create a dataframe with the values
  - return the dataframe

Block Of Code:
  - grab dataframe to use in order to calculate grades
  - dictionary = call function to convert dataframe to dictionary(dataframe)
  - calculated grades dataframe = call the calculate function(dictionary, dataframe)
  - write dataframe to a new csv file
  - print the dataframe that was returned

Output:
  - a dataframe which contians the grades from each section along with the total grade
  - a new csv file which shows information in dataframe
