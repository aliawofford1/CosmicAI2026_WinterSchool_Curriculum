**Multiple Choice Questions


1. What is the purpose of the .strip() method when processing text data from files?  
    a) To convert the string to uppercase.  
    b) To remove leading and trailing whitespace characters (like newlines or spaces).  
    c) To split the string into a list of words.  
    d) To count the number of characters in the string.

2. What is the benefit of using with open(...) as f: when handling files?  
    a) It automatically converts file content to a specific data type.  
    b) It automatically closes the file, even if errors occur, ensuring resource management.  
    c) It makes file reading significantly faster.  
    d) It prevents any data from being written to the file.

3. What does the line.split(',') method do when applied to a string read from a file?  
    a) It joins the string with commas.  
    b) It removes all commas from the string.  
    c) It splits the string into a list of substrings, using the comma as a delimiter.  
    d) It counts the number of commas in the string.

4. The CSV (Comma Separated Values) format is commonly used for:  
    a) Storing image data.  
    b) Storing spreadsheet and database data.  
    c) Storing binary executable files.  
    d) Storing encrypted information.
5. What distinguishes an absolute path from a relative path in Python file handling? 
a) An absolute path traces from the root directory, whereas a relative path references the active directory.
b) An absolute path is strictly for reading, while a relative path permits writing as well.  
c) Absolute paths apply to local storage, whereas relative paths target web locations.  
d) Absolute paths automatically construct absent folders, whereas relative paths do not.
6. What outcome occurs when executing this script on a multi-line document?  

    a) The target contents are fetched into a lone text string.  
    b) Merely the initial entry is stored inside lines.  
    c) Every line is gathered into a list of strings.  
    d) The document text is broken into distinct words within a list.

7. What main task is fulfilled by csv.reader() during CSV operations?  
    a) Automatically transforming numerical entries into integer types.  
    b) Iterating row by row to separate elements by the chosen character.  
    c) Purging missing entries and duplicate records automatically.  
    d) Converting flat files directly into pandas DataFrame structures.

8. Review the snippet below. What result will occur upon execution?  

    a) The second call wipes out the initial entry.  
    b) Python throws an exception due to prior file activity.  
    c) Both string entries are saved, with the second appended following the first.  
    d) The primary record persists on disk while the secondary record renders strictly to stdout.

9. Which statement accurately contrasts Python's standard csv module against the pandas library?  
    a) The csv library handles raw text exclusively, whereas pandas parses numeric tables exclusively.  
    b) The standard csv module handles statistical routines, whereas pandas functions as a basic view tool.  
    c) The native csv tools demand a DataFrame format, whereas pandas relies on basic list types.  
    d) The built-in csv package handles fundamental input/output operations, whereas pandas offers DataFrames for structured evaluation.

10. What sets direct iteration over a file using a for loop apart from invoking .readlines() beforehand?  
    a) Direct for loop iteration streams content line by line, whereas .readlines() loads all lines into a list in memory.  
    b) A standard loop trims spacing automatically, whereas .readlines() maintains original indentation.  
    c) Looping processes numbers exclusively, whereas .readlines() handles text streams.  
    d) Iterating via a loop terminates access automatically, whereas .readlines() leaves the stream active.
11. Which of the following is a 1-dimensional labeled array in Pandas?  
    a) DataFrame  
    b) Series  
    c) Array  
    d) List
12. The sum of the diagonal elements of a square matrix is known as its:  
    a) Determinant.  
    b) Inverse.  
    c) Trace.  
    d) Rank.
13. A Pandas DataFrame is best described as a:  
    a) 1D array.  
    b) 2D labeled data structure with columns that can be of different types.  
    c) Collection of key-value pairs.  
    d) Single row of data.
14. Which method is commonly used to load data from a CSV file into a Pandas DataFrame?  
    a) pd.load_csv()  
    b) pd.read_csv()  
    c) pd.get_csv()  
    d) pd.import_csv()
15. What does the .head() method typically display when applied to a Pandas DataFrame?  
    a) The last 5 rows of the DataFrame.  
    b) The first 5 rows of the DataFrame.  
    c) A summary of the DataFrame's columns.  
    d) The data types of each column.

16. Which NumPy function is used to create an array filled with zeros?  
    a) np.empty()  
    b) np.one()  
    c) np.zeros()  
17. What is the purpose of the axis parameter when performing statistical operations on a multidimensional NumPy array?
a) It specifies the number of dimensions in the array.
b) It determines the direction along which an operation, such as calculating the mean or sum, is performed.
c) It changes the data type of the elements stored in the array.
d) It determines the maximum number of elements an array can contain.
18. What is "modularization" as an advantage of using functions?  
    a) It makes the code run faster.  
    b) It allows a complex program to be broken down into smaller, simpler, and manageable parts.  
    c) It automatically handles all input and output operations.  
    d) It adds security to the program.
19. What is "code reuse" as an advantage of using functions?  
    a) Writing the same code multiple times in different parts of the program.  
    b) Copying and pasting code segments frequently.  
    c) Using the same function multiple times in different parts of a program or in different programs.  
    d) Reversing the order of code execution.
20. What is the role of the parentheses () after a function name when it's being called?  
    a) They indicate the end of the function definition.  
    b) They contain the arguments being passed to the function.  
    c) They mark the function as a built-in function.  
    d) They are optional and can be omitted.
21. Consider the function definition: def greet(name):. What does name represent in this context?  
    a) A local variable initialized inside the function.  
    b) A global variable.  
    c) A parameter.  
    d) The return value of the function.
22. What is \__annotations_\_?  
    a) A built-in function that describes the purpose of a function.  
    b) A special attribute that stores metadata about function parameters and return values.  
    c) A mandatory keyword for all function definitions.  
    d) The name given to a function that performs mathematical operations.



**Solution Key**

#### **Multiple Choice Answers**

 b) To remove leading and trailing whitespace characters (like newlines or spaces).
 b) It automatically closes the file, even if errors occur, ensuring resource management.
 c) It splits the string into a list of substrings, using the comma as a delimiter.
 b) Storing spreadsheet and database data.
a)  An absolute path traces from the root directory, whereas a relative path references the active directory.
c) Every line is gathered into a list of strings.
b) Iterating row by row to separate elements by the chosen character.
c)  Both string entries are saved, with the second appended following the first.
d) The built-in csv package handles fundamental input/output operations, whereas pandas offers DataFrames for structured evaluation.

a)Direct for loop iteration streams content line by line, whereas .readlines() loads all lines into a list in memory.





11. b) Series
12. c) Trace
13. b) 2D labeled data structure with columns that can be of different types.
14. b) pd.read_csv()
15. b) The first 5 rows of the DataFrame.
16. c) np.zeros()
17. b) It determines the direction along which an operation, such as calculating the mean or sum, is performed.
18. b) It allows a complex program to be broken down into smaller, simpler, and manageable parts.
19. c) Using the same function multiple times in different parts of a program or in different programs.
20. b) They contain the arguments being passed to the function.
21. c) A parameter.
22. b) A special attribute that stores metadata about function parameters and return values.










