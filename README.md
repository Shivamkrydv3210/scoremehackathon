For File test3.pdf
Open your terminal or command prompt.

Navigate to the directory where pdf_extractor.py is located.

Ensure that your PDF file test3.pdf is in the specified location (e.g., C:\Users\DELL\Downloads\test3.pdf).

Run the script with MODE set to statement or tables as desired. For example, if you want to parse statement lines:

```python pdf_extractor.py```

(Make sure the script's pdf_path variable is set to the location of test3.pdf and MODE is set accordingly.)

For File test6.pdf
Change the pdf_path variable inside pdf_extractor.py to point to your test6.pdf file, for example:

```pdf_path = r"C:\Users\DELL\Downloads\test6.pdf"```

Save the changes.

Run the script from the terminal again:

```python pdf_extractor.py```


Additional Notes
Switching Modes:
Edit the MODE variable at the bottom of the script to either "statement" (for line-based statement parsing) or "tables" (for extracting structured tables).

Output:
The script creates an extracted_tables folder where it saves the resulting Excel files:

For statement parsing: <PDF_Name>_statement.xlsx

For table extraction: <PDF_Name>_tables.xlsx

Dependencies:
Ensure the libraries are installed using the pip command provided.
