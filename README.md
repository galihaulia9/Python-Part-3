# Python-Part-3
The third week studied NumPy, Pandas, Loc &amp; iloc, Data Frame, Dataset (Titanic.csv) to be displayed to the data frame and adaptation questions from Python Mini Projects.

## NumPy
Is a Python library that focuses on scientific computing. Simply put : Numpy provides ready-to-use functions to help us perform scientific calculations such as matrices, algebra, statistics, and so on. Numpy example with displaying data types :

<img width="242" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/38febde0-0a44-4bef-af2c-5584a9ab486d">

- NumPy has several dimensions in the array, for example :
  
<img width="273" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/bbe3fc0e-e35b-44d8-ad5b-6c85f9d461a1">

## Pandas
Pandas is an open source library in the Python programming language that is often used to process data, from data cleaning, data manipulation, to data analysis. Pandas is based on another package called NumPy that supports multidimensional arrays.
- Pandas has two objects, namely series and data frames. 
This is an example of an Object Series :
<img width="213" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/f2b1b787-9644-4b2c-93b4-1936b5582b2b"> 

This is an example of a Data Frames :

<img width="392" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/03a291d5-ac1d-443e-a9f3-fd8f57414f38">

## Loc (location)
Loc is a function used to select data that is in the middle or between a series of data in a data frame or used to call its explicit index.
Example of using an explicit index and implicit index :

<img width="306" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/3f520cbc-04f5-4fc5-a1f7-cee4e82edbed">

<img width="283" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/c3510161-d601-4d17-a573-08444e663ba4">

## iloc (index location)
iloc (index location) is a function used to select data from one row to another and from one column to another or used to call its implicit index (index in Python arrays).
Example of using an explicit index and implicit index :

<img width="280" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/464e1597-b831-4879-9372-1b3ca21f868f">

<img width="285" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/ee7779e8-823b-4d87-ab22-eabdb2c92502">

## Data Frame
Data Frame is a collection of series with at least one series and is in the form of a table with a two-dimensional array of rows and columns. 
Here's an example of how to create a data frame from dictionary data type converted to series :
- Population
   
<img width="474" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/ae07f92a-8a05-4518-9e4a-e999834b0401">

- Extensive
<img width="387" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/765b034d-204e-4e7b-b0eb-0fbe39ca2008">

- Data Frame display when called
<img width="393" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/f3ead4f5-0709-42b4-b50d-9b6aab6fa35c">

## Functions Pandas Python
- df.head() : to view data from the top.
- df.info() : to view data information.
- df.tail() : to view data from the bottom.
- df.notnull().sum() : to see the amount of data that is not zero.
- df.isnull().sum() : to see the number of data with zero value.
- df.sum() : to see the sum of the data.
- df.shape : to view the number of rows and number of columns.
- df.columns : to view columns.
- df.index : to view the index.
- df.describe() : to display information from columns in the form of numbers.
- df['A'].mean() : to display the mean of a column e.g. A.
- df['A'].median() : to display the median of a column e.g. A.
- df['A'].mode()[0] : to display the mode of the column e.g. A.
- df['A'].min() : to display the minimum of a column e.g. A.
- df['A'].max() : to display the maximum of a column e.g. A.

## Dataset (Titanic.csv)
Example dataset (Titanic.csv) to be displayed into the data frame by using some of the functions described above :

<img width="718" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/d792dd64-109a-46cf-8767-0d1f439bf591">

<img width="680" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/bbd2482e-5037-4c83-a27d-07b23fbf9522">

<img width="486" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/a96a014d-ca91-4283-92d1-8f8ee7d6b9c8">

<img width="457" alt="image" src="https://github.com/galihaulia9/Python-Part-3/assets/125258524/1107cdb5-a964-4a51-87d7-082f1d536ee7">
















