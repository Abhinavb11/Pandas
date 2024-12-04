

---

# Pandas Data Analysis in Colab

This repository contains a Jupyter notebook created in **Google Colab** that demonstrates data manipulation and analysis using **pandas**. The notebook covers a variety of topics, from basic data structures to advanced data wrangling techniques.

## Contents

- **Notebook:**  
  [`pandas_data_analysis.ipynb`](./pandas_data_analysis.ipynb)  
  This notebook includes:
  - Introduction to pandas and data structures (`Series`, `DataFrame`)
  - Reading and writing data (CSV, Excel, JSON, etc.)
  - Data cleaning and preprocessing
  - Data transformation and aggregation
  - Handling missing data
  - Grouping and pivot tables
  - Merging and joining datasets

- **Sample Data:**  
  The notebook uses sample datasets that can be loaded directly from online sources or local files.

## Requirements

To run the notebook locally, you will need:

- **Python 3.x**
- **Jupyter Notebook** or **JupyterLab**
- The following Python libraries:
  - `pandas`
  - `numpy`
  - `openpyxl` (for Excel file support)

You can install the libraries using pip:

```bash
pip install pandas numpy openpyxl
```

## Running the Notebook

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/pandas-colab.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd pandas-colab
    ```

3. Open the notebook:

    ```bash
    jupyter notebook pandas_data_analysis.ipynb
    ```

4. Select the code cells and run them in sequence.

## Example Operations

Here are some of the operations you will learn to perform in this notebook:

- **Loading a DataFrame:**

  ```python
  import pandas as pd
  df = pd.read_csv('data.csv')
  ```

- **Basic Statistics:**

  ```python
  df.describe()
  ```

- **Grouping and Aggregating:**

  ```python
  df.groupby('category')['sales'].sum()
  ```
