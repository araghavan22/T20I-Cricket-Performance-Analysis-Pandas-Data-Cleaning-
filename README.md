# Cricket Stats Cleanup: A Pandas Data Wrangling Project

![Visualizing the power of data analysis in cricket performance](https://github.com/araghavan22/T20I-Cricket-Performance-Analysis-Pandas-Data-Cleaning-/blob/main/Cricket_Data_Analysis_Using_Python.png)

This repository contains a Jupyter Notebook (`Python_Pandas_Data_Cleaning_Cricket_Data.ipynb`) that demonstrates various data cleaning and analysis techniques using the Pandas library in Python. The project focuses on a dataset of cricket player statistics, specifically "Most runs in T20Is".

## Table of Contents

* [Project Overview](#project-overview)
* [Data Source](#data-source)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Dependencies](#dependencies)
* [License](#license)
* [Contact](#contact)

## Project Overview

The main objective of this project is to clean and prepare a raw dataset of cricket player statistics for analysis. It involves standard data wrangling procedures such as renaming columns, handling missing values, extracting relevant information from mixed data types, and converting data into appropriate formats. Subsequently, the cleaned data is used to derive insights, such as career length and average player performance metrics per country.

## Data Source

The dataset used in this analysis is derived from cricket player statistics, specifically focusing on "Most runs in T20Is". The raw data is expected to be in a CSV file named `Python-Data-Cleaning-Cricket-Most_runs_in_T201s.csv`.

The original source for the data is indicated as ESPNcricinfo's records for most runs in career:
[https://www.espncricinfo.com/records/most-runs-in-career-282827](https://www.espncricinfo.com/records/most-runs-in-career-282827)

## Features

* **Data Loading:** Reads cricket player statistics from a CSV file into a Pandas DataFrame.
* **Column Renaming:** Standardizes column names for better readability and usability (e.g., `Mat` to `Matches`, `NO` to `Not_Outs`, `HS` to `Highest_Inns_Score`, `BF` to `Balls_Faced`, `SR` to `Batting_Strike_Rate`).
* **Missing Value Handling:** Identifies and addresses missing values, including filling `NaN` values in `100` and `0` columns with zeros and `Not_Outs` with the median.
* **Data Type Conversion:** Cleans and converts relevant columns (e.g., `Highest_Inns_Score`, `Player`, `Span`) to appropriate numerical and categorical data types.
* **Feature Engineering:** Extracts `Rookie_Year`, `Final_Year`, and `Country` from existing columns and calculates `Career_Length` for each player.
* **Aggregated Analysis:** Provides insights into cricket statistics by country, including average runs, centuries, half-centuries, fours, sixes, ducks, career length, matches, and innings.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Place the data file:** Ensure that the `Python-Data-Cleaning-Cricket-Most_runs_in_T201s.csv` file is in the same directory as the Jupyter Notebook.
2.  **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook Python_Pandas_Data_Cleaning_Cricket_Data.ipynb
    ```
3.  Execute the cells in the notebook sequentially to perform data cleaning and analysis.

## Dependencies

The project primarily relies on the following Python library:

* Pandas

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For any questions or suggestions, please contact : https://www.linkedin.com/in/abha-raghavan/.
