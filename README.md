# Research

**Overview**

The code is a Python program that allows users to search for keywords within PDF files. The program uses the tkinter GUI library to display a file selection window and a table showing the search results. Users can enter multiple keywords to search for and the program will highlight these keywords in the extracted text from the PDF files.

**Dependencies**

The program uses several external libraries that need to be installed before running the code:

re
tkinter
pandas
glob
PyPDF2
os
nltk

**How to Use**

Run the Python program.
Click the "Choose Directory" button to select the folder containing the PDF files you want to search.
Enter the keywords you want to search for in the "Submit General/Highlight", "Submit Specific", and "Submit Tokenized" fields. The first field is for general keywords, while the second and third fields are for specific keywords and tokenized keywords, respectively.
Click the "Search" button to search for the keywords in the PDF files.
The program will display a table showing the file names and the extracted text with the keywords highlighted. Users can click on a row to see the details of the search result.
Users can click the "Save Results" button to save the search results as an Excel file.

**Functions**

The program contains several functions:

search_textbox(): Highlights the extracted text containing the keywords.
get_selection(): Displays the details of the selected search result.
submit_keywords(), submit_specific(), and submit_token(): Adds the keywords entered by the user to the search list.
clear_keywords(): Clears the search list.
save_as_excel(): Saves the search results as an Excel file.
search_PDF(): Searches for the keywords in the PDF files.
search_PDF1(): Extracts text from a PDF file and searches for the keywords.
clear_tree(): Clears the search results table.

**Disclaimer**

Please note that this code is provided as-is and may contain bugs or errors. The code is intended for educational purposes only and should not be used for any other purpose. The author assumes no responsibility or liability for any damage or loss caused by the use of this code.
