# Juniper Networks Solution

# Goal: 
The goal of this exercise is to develop a fuzzy record matching program that takes records from “query” set and finds matching record in the “reference” set. 

#Data:
In the attached excel file, there are two sheets:
-	“reference” sheet  contains a list of restaurants, its address and cuisine (“reference” set) 
-	“query” sheet contains again a list of restaurants, its address and cuisine, plus two additional columns (“query” set)
-	“reference_id” column needs to be populated using the fuzzy record matching program
-	“score(optional)” field can show to what degree the record matches or the confidence of the match. It is optional though

## Dataset

Dataset used in this project is the file "Data-for-Ex1-restaurant-nophone.xlsx"

## Install

### &nbsp;&nbsp;&nbsp; Supported Python version
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Python version used in this project: 3.6.8

### &nbsp;&nbsp;&nbsp; Libraries used

> *  [Pandas](http://pandas.pydata.org) 0.24.2
> *  [Numpy](http://www.numpy.org) 1.16.2
> *  [fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/) 0.17.0


## Approach
1. Importing the libraries and data.
2. Function that takes records from “query” set and finds matching record in the “reference” set. 
3. Conclusion.

## Code

The code used in this project is inside **Juniper_Solution.ipynb**.

## Run

To run this project you will need some software, like Anaconda, which provides support for running .ipynb files (Jupyter Notebook).

## Conclusion

Manually validated the outcome and I could see the solution is 100% Accurate.
