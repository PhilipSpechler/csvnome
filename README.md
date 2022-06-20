# csvnome
Do you ever wish you could take a quick peek inside a csv file without having to open excel or a text editor?  
Good News! This little script can quickly make sense of your largest big data matrix.

Add csvnome to your path and this script will become your new favorite command line tool

Running csvnome will display key info about your csvfile including--
* matrix shape
* column header names
* Signs of excessive or missing data  

See a column name (or two, or twelve) you want to know more about?
Run it again while specifying the column names or indices to retrieve the min, max, mean, and frequency distribution!

## From the docstring:
This is a python tool used to get a fast look at the contents of a given csv.

Run it from the command line!

BASIC USAGE:  
$ csvnome <csv_file_name>   

if pwd does not contain your csv--  
$ csvnome <full_path_to_csv>

OPTION:  
To display basic stats of a given column,
give column index number -and/OR- column name
  
$ csvnome <csv_file_name> <column_names_or_indices>

*Use commas to separate all your columns of interest*

ex.) Display stats for column 4,5,10,age,weight  

$ csvnome mycsvfile.csv 4,5,10,age,weight

## Dependencies
Written in python2.x

Updated June 2022 For Python3 (finally)
