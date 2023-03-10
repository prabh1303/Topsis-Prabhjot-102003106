# Topsis-Prabhjot-102003106

## What is TOPSIS
Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) originated in the 1980s as a multi-criteria decision making method.
<br> 
TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.

## Installation
```pip install Topsis-Prabhjot-102003106```

## Input csv format
Input file must contain three or more columns
<br>
First column is the object/variable name 
<br>
2nd to last columns contain numeric values only

## How to use it
Python File<br>
```
which includes complete code for topsis calculation
```
Command Prompt<br>
```
python <python_file> <Input Data File> <Weights> <Impacts> <Result File Name>
```
<br>

Example:<br>
```
python codefile.py inputfile.csv “1,1,1,1,2” “+,+,+,+,-” result.csv
python 102003106.py 102003106-data.csv “1,1,1,1,2” “+,+,+,+,-” 102003106-result.csv
```
<br><br>
<i>Note: The weights and impacts should be ',' seperated, input file should be in pwd.</i> 

## Functions and Return Values

```
function = topsis_calc()
return values = Creates a csv file with the topsis rank and performance score
```

## Sample input data
| Fund Name       | P1 | P2 | P3 | P4 | P5 |
| ------------- |:-------------:| -----:|-----:|-----:|-----:|
| M1    | 0.62 | 0.38 | 3.8 | 33.8 | 9.65  | 
 | M2    | 0.75 | 0.56 | 5.7 | 50.3 | 14.33 | 
 | M3    | 0.95 | 0.90 | 6.5 | 65.6 | 18.49 | 
 | M4    | 0.61 | 0.37 | 6.2 | 43.6 | 12.70 | 
 | M5    | 0.60 | 0.36 | 6.4 | 61.2 | 17.14 | 
 | M6    | 0.76 | 0.58 | 5.3 | 68.0 | 18.66 | 
 | M7    | 0.66 | 0.44 | 6.2 | 47.2 | 13.63 | 
 | M8    | 0.80 | 0.64 | 5.7 | 37.1 | 11.06 | 


## Sample output data
| Fund Name       | P1 | P2 | P3 | P4 | P5 | Topsis Score | Rank |
| ------------- |:-------------:| -----:|-----:|-----:|-----:| ---: | ---: |
| M1    | 0.62 | 0.38 | 3.8 | 33.8 | 9.65  |  0.317272185       | 8           | 
| M2    | 0.75 | 0.56 | 5.7 | 50.3 | 14.33 |  0.452068871       | 4           | 
| M3    | 0.95 | 0.90 | 6.5 | 65.6 | 18.49 |  0.689037307       | 1           | 
| M4    | 0.61 | 0.37 | 6.2 | 43.6 | 12.70 |  0.340383903       | 7           | 
| M5    | 0.60 | 0.36 | 6.4 | 61.2 | 17.14 |  0.367206376       | 6           |
| M6    | 0.76 | 0.58 | 5.3 | 68.0 | 18.66 |  0.481350901       | 3           | 
| M7    | 0.66 | 0.44 | 6.2 | 47.2 | 13.63 |  0.372999972       | 5           | 
| M8    | 0.80 | 0.64 | 5.7 | 37.1 | 11.06 |  0.51226635        | 2           | 
