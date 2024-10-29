# Automated-Data-Cleaning-and-Visualization-Tool

Overview
The Automated Data Cleaning and Visualization Tool is designed to streamline the process of preparing datasets for analysis. This tool allows users to upload their own CSV files, automatically clean the data by handling missing values and outliers, and visualize the cleaned dataset with various plots. It aims to simplify data preprocessing, enabling data scientists and analysts to focus more on their analysis tasks.

Features
CSV File Upload: Users can easily upload their datasets in CSV format.
Automated Data Cleaning:
Fills missing values with the median for numerical columns.
Removes duplicate entries to ensure data integrity.
Identifies and removes outliers using the Z-score method.
Data Visualization:
Displays summary statistics for numerical features.
Generates pair plots to visualize relationships between numerical features.
Creates box plots to illustrate the distribution of numerical features and identify potential outliers.
Download Cleaned Data: Users can download the cleaned dataset as a CSV file after processing.
Installation
This project is designed to run in Google Colab. To get started:

Open Google Colab.
Create a new notebook.
Copy and paste the provided code into a cell.
Run the cell to install any required libraries.
Usage
Run the cell to prompt for a CSV file upload.
After uploading, the tool will clean the dataset and generate visualizations.
View the summary statistics and visualizations in the output cells.
Download the cleaned dataset directly from Colab.
Example
Here's a quick example of how to use the tool:

Contribution
Contributions to enhance the tool are welcome! If you have suggestions for improvements, additional features, or bug fixes, please fork the repository and submit a pull request. You can also open an issue to discuss potential changes.
