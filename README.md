#   Housing Price Analysis

This Jupyter Notebook (`Housing_tamrin.ipynb`) performs an analysis on housing data. It includes data loading, data type conversion, feature engineering, and exploratory data analysis.

##  Libraries Used

* **pandas:** For data manipulation and analysis.
* **numpy:** For numerical operations.
* **seaborn:** For enhanced data visualization.
* **matplotlib.pyplot:** For creating visualizations.

##  Data Description

The data is contained in the `housing.csv` file and includes the following columns:

* **price:** Price of the house.
* **area:** Area of the house.
* **bedrooms:** Number of bedrooms.
* **bathrooms:** Number of bathrooms.
* **stories:** Number of stories.
* **mainroad:** Whether the house is on the main road (yes/no).
* **guestroom:** Whether the house has a guest room (yes/no).
* **basement:** Whether the house has a basement (yes/no).
* **hotwaterheating:** Whether the house has hot water heating (yes/no).
* **airconditioning:** Whether the house has air conditioning (yes/no).
* **parking:** Number of parking spots.
* **prefarea:** Whether the house is in a preferred area (yes/no).
* **furnishingstatus:** Furnishing status of the house (furnished, semi-furnished, unfurnished).

##  Data Processing

The notebook performs the following data processing steps:

1.  **Data Loading:** Loads the data from `housing.csv` into a pandas DataFrame.
2.  **Data Inspection:**

    * Displays the first 5 rows of the DataFrame using `df.head()`.
    * Displays information about the DataFrame, including column names, data types, and non-null counts using `df.info()`.
    * Displays the data types of the columns using `df.dtypes`.
    * Calculates the total number of missing values.
    * Counts the occurrences of each unique value in the 'furnishingstatus' column.
3.  **Feature Engineering:**

    * Converts 'price' from its original unit to millions.
    * Converts 'area' from its original unit to thousands.
    * Calculates 'price/area'.
4.  **Data Type Conversion:** Converts specified columns to the 'category' data type.

##  Exploratory Data Analysis and Visualization

The notebook includes exploratory data analysis:

* Displays the first 2 rows of the transformed DataFrame.
* Includes a placeholder for further visualizations (indicated by `---` and an empty code cell intended for plotting).
* Creates a heatmap of the correlation matrix.

##  How to Use

1.  **Prerequisites:**

    * Python 3.x
    * pandas
    * numpy
    * matplotlib
    * seaborn
2.  **Installation:**

    * Install the required libraries using pip:

        ```bash
        pip install pandas numpy matplotlib seaborn
        ```
3.  **Execution:**

    * Place the `housing.csv` file in the same directory as the notebook.
    * Run the Jupyter Notebook (`Housing_tamrin.ipynb`) to execute the analysis.

# Price-House-Analysis-2
