# Task-1
## Dataset:I took SampleSuperstore data as Dataset

A superstore is a very large supermarket, often selling household goods, clothes, and electrical goods, as well as food. Superstores typically charge anywhere from 15 to 45 percent less than their smaller counterparts.

## process
1)I uploaded the SampleSuperstore.csv file in jupyter notebook

2)Then started changes 

## Project Structure
The project is organized in a Jupyter Notebook (Task_1.ipynb) which performs the following tasks:

1)Data Loading: The dataset is loaded into a pandas DataFrame.

2)Initial Exploration: Basic information about the dataset is examined, including data types and summary statistics.

3)Data Cleaning:

Handling missing values (though none were found initially).

3)Removing duplicate rows.

Standardizing text columns (converting to lowercase and stripping whitespace).

Cleaning column names (converting to lowercase and replacing spaces with hyphens).

Converting data types for consistency (e.g., postal codes to strings).

4)Exporting Cleaned Data: The cleaned dataset is saved as a new CSV file (cleaned_sample_superstore.csv).

## Key Steps
1)Handling Missing Values: The dataset was checked for missing values, and none were found. A forward-fill method was applied as a precaution.

2)Removing Duplicates: Duplicate rows were identified and removed to ensure data integrity.

3)Standardization: Text columns like City, State, and Category were standardized to lowercase for consistency.

4)Column Name Cleaning: Column names were cleaned to follow a consistent format (e.g., Ship Mode became ship_mode).

5)Data Type Conversion: Columns like Postal Code were converted to strings, and numeric columns were ensured to have the correct data types.

## Output
The cleaned dataset (cleaned_sample_superstore.csv) is ready for further analysis or visualization.

## How to Use
Clone the repository.

Open the Jupyter Notebook (Task_1.ipynb) to see the step-by-step cleaning process.

Use the cleaned dataset (cleaned_sample_superstore.csv) for your analysis.

## Requirements
Python3.12 or lattest version
python library Pandas
Jupyter Notebook
