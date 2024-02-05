# css4p01.py
lurl ink for the python file 
# -*- coding: utf-8 -*-
"""
Created on Mon Feb  5 22:29:43 2024

@author: hp i7
"""

# Import necessary libraries
import pandas as pd
import numpy as np

data = pd.read_csv('movie_data.csv')  # Assuming your data is in a CSV file

# Display basic information about the dataset
print("Basic Information about the Dataset:")
print(data.info())

# Display the first few rows of the dataset
print("\nFirst few rows of the Dataset:")
print(data.head())


# Save the cleaned data to a new CSV file
cleaned_data.to_csv('cleaned_data.csv', index=False)


