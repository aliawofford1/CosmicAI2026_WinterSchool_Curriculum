

1. Explain the difference between file.readline() and file.readlines() when reading content from a text file. When would you use each?

2. Describe the purpose of using the with open(...) as f: statement for file handling in Python. What advantage does it offer over manually calling f.close()?

3. What is a CSV file, and why is it a common format for data exchange? How would you typically read a CSV file line by line in Python, assuming it uses commas as delimiters?
4. Explain the difference between using .read(), .readline(), and .readlines() when working with text files in Python. Describe a situation in which reading a file line by line would be preferable to reading the entire file at once. 
5. Describe the difference between using Python's built-in csv module and the pandas library to read a CSV file. What is a pandas DataFrame, and how does it help organize tabular data?

6. Describe the key differences and typical use cases for Pandas Series and Pandas DataFrames.

7. Explain the concept of "Data Manipulation" in Pandas and provide two examples of common data manipulation tasks.

8. What are Universal Functions (UFuncs) in NumPy, and why are they important for efficient numerical computations?
 
#### **Short Answer Solutions**

1. **Explain the difference between file.readline() and file.readlines() when reading content from a text file. When would you use each?**

  - **file.readline():** This method reads only _one line_ from the file at a time. Each subsequent call to readline() returns the next line, including the newline character (\\n) at the end of the line. It's useful for processing files line by line, especially for very large files that might not fit entirely into memory, or when you need to handle specific lines differently based on their content.
  
- **file.readlines():** This method reads _all lines_ from the file and returns them as a list of strings, where each string in the list represents a line from the file (including the newline character). It's suitable for smaller files where you need to load all content into memory for subsequent processing, such as searching or parsing the entire file.

2. Describe the purpose of using the with open(...) as f: statement for file handling in Python. What advantage does it offer over manually calling f.close()? 
 
    The with open(...) as f: statement is a context manager for file handling in Python. Its primary purpose is to ensure that a file is properly closed after its block of code is executed, regardless of whether the code runs successfully or encounters an error.  
    The main advantage it offers over manually calling f.close() is that it guarantees the file will be closed automatically. If you open a file manually and forget to call f.close() or if an error occurs before f.close() is reached, the file might remain open, leading to resource leaks, data corruption, or "permission denied" errors in subsequent operations. The with statement handles these scenarios gracefully, making code more robust and preventing common file-handling issues.

3. What is a CSV file, and why is it a common format for data exchange? How would you typically read a CSV file line by line in Python, assuming it uses commas as delimiters?  
    A CSV (Comma Separated Values) file is a plain text file that uses commas to separate values. Each line in the file represents a row of data, and the values within that row are separated by commas.  
    It is a common format for data exchange because:
   **Simplicity:** It's human-readable and easy to understand.
   **Compatibility:** Most spreadsheet software (like Excel, Google Sheets) and databases can easily import and export data in CSV format.
  - Lightweight: It's a relatively small file size compared to other structured data formats.  
        To typically read a CSV file line by line in Python, you can open the file in read mode and iterate through its lines. Then, you use the .split(',') method on each line to separate the values. It's also good practice to use .strip() to remove the newline character from the end of each line.  
        Example:
- Python

with open('my_data.csv', 'r') as file:

for line in file:

data_fields = line.strip().split(',')

print(data_fields)

4. Explain the difference between using .read(), .readline(), and .readlines() when working with text files in Python. Describe a situation in which reading a file line by line would be preferable to reading the entire file at once. 
.read() retrieves the remaining file content as a string; .readline() retrieves one line; .readlines() retrieves the remaining lines as a list. Reading line by line is useful for processing larger files without loading the entire contents into memory.
5. Describe the difference between using Python's built-in csv module and the pandas library to read a CSV file. What is a pandas DataFrame, and how does it help organize tabular data?
The csv module supports row-by-row reading and writing of CSV data. pandas provides a higher-level interface for loading and manipulating tabular data. A DataFrame is a two-dimensional structure with labeled rows and columns.
