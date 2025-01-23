# Automated Data Validation for Handgrip Strength Measurements

## Project Overview
This project automates the validation process for handgrip strength data collected from research tools. It addresses the challenge of managing and analyzing large volumes of data spread across multiple Excel files, typically one file per measurement. To help you get started, I have included a sample dataset (sample_data.csv) that represents the type of data this tool is designed to process. Please feel free to leave any feedback :)

## Key Features
1. **Automated Data Processing**: Efficiently processes hundreds or thousands of Excel files.
2. **Visualization**: Generates line graphs for each Excel file in PDF format.
3. **Participant-Centric Grouping**: Groups results by participant, displaying multiple measurements on a single PDF page.
4. **Data Extraction**: Extracts key metrics such as highest handgrip strength.
5. **Test Segregation**: Splits data by test number (1, 2, or 3) for easy comparison.
6. **Customizable Analysis**: Flexibility to gather or create additional types of information as needed.

## Why This Tool?
Research involving handgrip strength, eyetracking, and similar measurements often produces individual Excel files for each data point. Manual validation of such large datasets is time-consuming and error-prone. This tool streamlines the process, saving time and improving accuracy.

## How It Works
1. **Data Input**: The script scans through all Excel files in a specified directory.
2. **Data Processing**: For each file, it performs two main tasks:
   a. **Visualization**: Creates line graphs representing the data.
   b. **Data Extraction**: Pulls out relevant metrics and information.
3. **Output Generation**:
   a. Produces PDF files with line graphs, grouped by participant.
   b. Compiles extracted data into a summary format (e.g., CSV or Excel).

## Feedback
Your feedback is always welcome! Feel free to share any suggestions or improvements you might have.
