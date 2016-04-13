# CSV-reader
Command line tool to quickly read key info from a csv file.
Key info includes
-excessive or missing data
-variable min,max,mean
-response frequenceies for variable values

From the docstring:

This is a python tool used to look at the contents of a given csv

run it from the command line! (add to csvnome to your path)

***IMPORTANT***: 
Before runing, first change your working directory to 
the directory with the CSV file of interest

BASIC USAGE:
============
$ cd <path_with_csv_file>
$ csvnome <csvfile>

OPTIONS:
========

To display basic stats--
give column index number -and/OR- column name

$ csvnome <csvfile> <opts>

ex.) show stats for column 4,5,10,age,weight

$ csvnome mycsvfile.csv 4,5,10,age,weight
