# Python Beginners Guide Part 3
Welcome to the Python Beginners Guide Part 3! 🐍✨ 

Here, we explore Python, delving deep into the realms of NumPy and Pandas. This space is designed to be your guide, offering insights, tips, and practical examples for harnessing the power of Python in data manipulation and analysis. Whether you're just starting or an experienced coder, join us on this exciting journey through the world of Python, NumPy, and Pandas! 🚀📊

## Numpy
NumPy is a Python library that supports large, multi-dimensional arrays and matrices and a collection of mathematical functions to operate on these arrays. Arrays are efficient and fast for numerical operations. They enable you to work with large datasets more easily than standard Python lists.

### Dimension
In NumPy, the term "dimension" refers to the number of axes or directions in which data can vary. In NumPy, the ‘ndmin’ parameter is used when creating an array to specify the minimum number of dimensions the resulting array should have. It allows you to set the number of dimensions explicitly. 

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/c7410d6a-e177-4965-97c2-ea157a946ea4)

From the example above, we call 7 dimensions with the expression 'ndmin=7' where the number 7 can be filled as desired.

## Pandas
Pandas is a Python library for efficient data manipulation and analysis. It simplifies data cleaning, transformation, and analysis tasks with its DataFrame and Series data structures. Pandas are widely used in data science to handle structured data, perform statistical operations, and work with various file formats.

### Object Series
A Pandas Series is like a column in a table. It is a one-dimensional array holding data of any type. It is similar to a table column and can be considered a fixed-size dictionary, where the index labels map to the corresponding values.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/07430ab4-b7f0-470b-81f7-cd5845839d05)

#### Data Slicing
Slicing allows to selection of specific rows or columns from the data structure based on their labels or positions.

Explicit and Implicit Data Slicing
Explicit data slicing retrieves a subset of data with reference to an explicitly specified index, such as an index range or a specific index. An implicit data slicing retrieves a subset of data with reference to an implicitly specified index, such as a specific rule or condition where the last index is not included in the resulting subset of data.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/08f00791-25fb-4e4e-8539-fd32026c6e9c)

#### Loc &Iloc
Loc calls an explicit index, and an Iloc calls an implicit index. Loc and iloc are used to remove inconsistencies in data slicing.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/1cc305e2-a131-40ed-b70f-8178661473e3)
 
## DataFrame
DataFrame is a collection of series with at least 1 series. A DataFrame in Python is a two-dimensional, size-mutable, and potentially heterogeneous tabular data structure with labeled axes (rows and columns). It can be thought of as a table with rows and columns. For example, DataFrame is built by 3 series.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/92debff9-c08b-4cd3-816e-6f1631d22559)

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/d1ac9153-9e2e-4df6-8a35-01214b4aa63d)

## Load Data CSV in Pandas
To import a CSV file in Python, you can use the Pandas library, which provides a simple and efficient way to work with structured data. Make sure CSV data that has been uploaded in the same folder.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/e56d5617-c8d8-4dce-8ab4-88e960aa6d49)

Given the example of importing data 'Titanic.csv' with the “pd.read_csv()” function.

### Head
•	viewing from top data
•	can be customized
•	head by default is top 5

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/74b7928a-a39c-48ad-9be3-249301c6ff6b)

### Tail
•	tail()returns a specified number of last rows.
•	tail()returns the last 5 rows if a number is not specified.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/ed13695e-e9f0-45f6-8632-e1a697bc24ab)
 
### Info
•	info() method prints information about the DataFrame.
•	The information contains the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/b8284560-3819-48df-bb00-23638f4b1459)

### Shape
shape is the number of rows and columns of the DataFrame.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/4483f470-6e89-4d1e-886f-10fcbc028ceb)

891 is the number of rows, 12 is the number of columns

### Columns
columns returns the label of each column in the DataFrame.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/59448bfc-7aba-4e2a-bac7-402340bf39ba)

### Index
•	The index returns the index information of the DataFrame.
•	The index information contains the labels of the rows. If the rows have NOT named indexes, the index property returns a RangeIndex object with the start, stop, and step values.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/5ede1833-092a-4e90-b547-f375c213de2e)

### Sum
•	Returns the sum of the values in the specified axis
•	The sum() method adds all values in each column and returns the sum for each column.
•	By specifying the column axis (axis='columns'), the sum() method searches column-wise and returns the sum of each row.

### Isnull
Isnull is used to find NULL values.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/3a80720e-5cab-4ac0-a8a0-0b6b6a1c30f0)

### Notnull
Notnull is used to find values that are NOT NULL.

![image](https://github.com/MaulitaNurSejati/NumPy_Pandas/assets/135823289/4222a0a8-f7ad-4e1e-952c-278475dfa8e1)

### Describe
Returns a description summary for each column in the DataFrame

### Mean
•	Return the mean of the values in the specified axis
•	Mean: The average value

### Median
•	Median: The midpoint value
•	Return the median of the values in the specified axis

### Mode
•	Mode: The most common value
•	Returns the mode of the values in the specified axis

## The Python Journey Continues

With these additional Python concepts and control structures under your belt, you're well on your way to becoming a proficient Python programmer. The world of Python is vast and versatile, and there's always more to explore and learn.

As you continue your Python journey, don't hesitate to experiment, build projects, and collaborate with fellow learners and developers. The best way to learn is by doing, and Python offers endless possibilities for creativity and problem-solving.

Python's rich variety of data types, control structures, and functions make it a versatile and powerful language for various applications. So, dive in and continue exploring the exciting world of Python programming! 🚀

Happy coding! 🐍👨‍💻👩‍💻

### Min
Returns the min of the values in the specified axis

### Max
Return the max of the values in the specified axis
