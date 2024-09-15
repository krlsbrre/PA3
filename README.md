# Python Data Analysis (Pandas) - Programming Assignment 3
This repository contains the solution for Programming Assignment #3 focused on Python Data Analysis using Pandas.

## Description
This repository contains two Python-based data analytics problems:

### Problem 1: Loading and Viewing Data
- Load the `cars.csv` file into a Pandas DataFrame.
- Display the first and last five rows of the dataset.<br />
**Expected output:** <br />
   First 5 rows: ![image](https://github.com/user-attachments/assets/3ba77655-085b-44a8-91f6-7050515b92b7)
   Last 5 rows: ![image](https://github.com/user-attachments/assets/87b66da9-ee50-4077-b11c-c908c66587f5)

### Problem 2: Data Manipulation Using Pandas
1. **Subsetting**:  
   - Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7…) of cars.
   **Expected output:**
      ![image](https://github.com/user-attachments/assets/da480e12-9d9e-4f74-8a5a-5a817ce893ee)
2. **Indexing**:
   - Display the row that contains the ‘Model’ of ‘Mazda RX4’.
   **Expected output:**
      ![image](https://github.com/user-attachments/assets/de2e0485-65cd-43d7-9d07-d73ce580b296)
3. **Data Querying**:
   - How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?
   **Expected output:**
      ![image](https://github.com/user-attachments/assets/fe8da4ec-a4b3-47cf-b308-9b38107bcede)
4. **Complex Query**:
   - Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4 Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.
   **Expected output:**
      ![image](https://github.com/user-attachments/assets/ca6e6e03-a060-4ad5-90bc-23f3f8449faf)


## How `.py` Files Were Saved

The `.py` files for this assignment were saved using custom `filewrite()` and `fileread()` functions.

1. **`filewrite()`**:
   - This function is used to save a block of Python code into a `.py` file.
   - Example:
     ```python
     filecontent1 = """
     import pandas as pd
     cars_file = pd.read_csv('cars.csv')

     cars_file.head()
     cars_file.tail()
     """
     filewrite('Sabarre_Pandas-P1.py', filecontent1)
     ```
   - The above code writes the content of Problem 1 to a file named `Sabarre_Pandas-P1.py`.

2. **`fileread()`**:
   - This function is used to read the contents of a `.py` file and display it in the notebook.
   - Example:
     ```python
     fileread('Sabarre_Pandas-P1.py')
     ```

This approach ensures that the code is saved as `.py` files, which can be executed independently from the notebook.

## Getting Started

### Prerequisites
You need Python and `numpy` installed. To install `numpy`, run:

```bash
pip install numpy
```

## Running the code

#### 1. Clone the repository:
```bash
git clone https://github.com/krlsbrre/PA3.git
```
#### 2. Navigate to the project directory and drag & upload the .ipynb file to Jupyter Notebook


## Author

- [@krlsbrre - Karlos Louis M. Sabarre - 2ECE-A - 2023184838](https://www.github.com/krlsbrre)
