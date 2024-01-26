# About
The purpose of these Python script is to process an Excel file, extract specified fields from a JSON column, remove duplicate rows based on some specified columns, and save the modified DataFrame to a new Excel file.")

# Json-Extracts
Instructions for Running the Excel Processing Script


## Clone the Repository:

Clone this repository to your local machine using the following command:

git clone [https://github.com/your-username/your-repository.git](https://github.com/1Ayuba/Json-Extracts)
Navigate to the Script Directory:

## Change into the directory containing the script:

cd your-repository
Install Required Libraries:

### Ensure you have Python installed on your machine.
Install the required Python libraries using:
pip install pandas openpyxl
Run the Script:

## Execute the script by running the following command:

Farmer_json_extracts.py
Tags_json_extract.py

The script will first prompt you to enter your name. Provide the name and press Enter.

The script will prompt you to enter the Excel file name (including extension). Provide the file name and press Enter.
Review Output:

The script will print the modified DataFrame, and you will be prompted to enter the output Excel file name (including extension).
Save Output:

After entering the output file name, the modified DataFrame (with duplicates removed) will be saved to the specified Excel file.
Complete:

The script has now processed the Excel file, extracted specified fields from JSON_Serialization, removed duplicates based on the 'TagNo' column, and saved the modified DataFrame to a new Excel file.

## Note:

Ensure that the Excel file you provide exists in the same directory as the script.
The script uses the 'openpyxl' library for Excel reading/writing, so make sure it is installed (pip install openpyxl).
