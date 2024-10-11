# Most Visited Site Analysis

This project analyzes browser history data to determine the most visited site. The analysis is performed using a Jupyter Notebook.

## Project Structure


## Requirements

- Python 3.12.1
- pandas
- numpy

## Installation

1. Clone the repository:
    ```sh
    git clone "https://github.com/chetankumarpulipati/ms-edge-browsing-data-analysis.git"
    cd ms-edge-browsing-data-analysis
    ```

2. Install the required Python packages:
    ```sh
    pip install pandas
    ```

## Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook most-visited-site.ipynb
    ```

2. Run the cells in the notebook to execute the analysis.

## Functionality

Export browsing data from microsoft edge and store it in a location (preferred Desktop)

The main function in the notebook is `most_visited_site`, which reads a CSV file containing browser history and determines the most visited site.

3. To analyze the browser history data, set the file_path variable to the path of your CSV file and call the most_visited_site function:

file_path = 'BrowserHistory.csv'

most_visited = most_visited_site(file_path)

if most_visited:
<br>
    print(f"The most visited site is: {most_visited}")
