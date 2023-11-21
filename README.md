# python_DataCleaning_Bikesales
Utilizing Pandas in a Jupyter Notebook, this script cleans London Bikes dataset. It renames columns, normalizes data, converts codes to descriptive labels, ensuring clarity. The cleaned dataset is exported to 'london_bikes_final.xlsx' for further analysis.

# London Bikes Dataset Cleaning with Pandas

This Jupyter Notebook script demonstrates a systematic data cleaning process using the pandas library for the London Bikes dataset:

Reads the 'london_merged.csv' file into a pandas DataFrame ('bikes') and inspects its structure and data types.
Renames columns using a predefined dictionary for clarity and consistency.
Normalizes humidity values and converts numerical codes for 'season' and 'weather' into descriptive labels using mapping dictionaries.
Enhances data readability by converting specific columns to string data types for mapping operations.
Provides a preview of the cleaned dataset using the 'head()' function.
Exports the cleaned dataset into an Excel file named 'london_bikes_final.xlsx' for further analysis or sharing purposes.
This script serves as a practical guide for cleaning and structuring datasets, improving data clarity, and preparing it for downstream analysis or reporting.
