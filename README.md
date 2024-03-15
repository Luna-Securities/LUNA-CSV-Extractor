# Luna Securities CSV Extractor

## Overview
The Luna Securities CSV Extractor is a simple graphical user interface (GUI) application built using Python and Tkinter. It allows users to upload one or more Excel or CSV files containing financial data, process the data, view the results, and save the final output to a CSV file.

## Features
- Upload Excel or CSV files.
- Extract unique combinations of 'Security Symbol' and 'Security Name' from each file.
- Merge total values from each file into a master DataFrame.
- Sort the master DataFrame by 'Security Symbol' and 'Security Name'.
- Display the final output in a scrollable text area.
- Save the final DataFrame to a CSV file.
- User-friendly interface with file selection dialogs.

## Installation and Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/luna-securities-csv-extractor.git
2. **Navigate to the project directory:**
   ```bash
   cd luna-securities-csv-extractor

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt

3. **Run the application:**
- On Windows: Double-click the `Qoutes_Compiler.py` file.
- On Unix-based systems (Linux, macOS): Right-click the `Qoutes_Compiler.py` file, select "Open With" > "Python" or "Python Launcher".

4. **Usage:**
- Click the "Upload Excel/CSV" button to select one or more Excel or CSV files containing data.
- Once the files are uploaded, the application will process the data and display the final output in the text area.
- You can save the final output to a CSV file by clicking the "Save" button.

## Dependencies
- Python 3.x
- Tkinter (standard library)
- pandas
- openpyxl (if working with Excel files)

## Author
Janah Patricia Morano & Jan Christian Torres
