# Assignment-5-Data-1202

The Python code provided analyzes a YouTube channel dataset. To do this, it imports the pandas library as 'pd' to handle tabular data. A csv file named "youtube_dataset.csv" located in "C:\Users\aboom\Downloads" is loaded into a pandas DataFrame called 'df'. The file is encoded in ANSI.

After loading the dataset, the code uses the .head() method to display the first five rows of the DataFrame. The .columns attribute is used to check the column names, .size attribute to show the total number of elements in the DataFrame, and .shape attribute to show the number of rows and columns. The .dtypes attribute is used to display the data type of each column.

To verify that the DataFrame is sorted in descending order of subscribers, the code uses the .is_monotonic_decreasing attribute on the 'subscribers' column.

Lastly, a new function called 'answer1()' is defined to return a new DataFrame containing the first 1000 rows of the original DataFrame.
