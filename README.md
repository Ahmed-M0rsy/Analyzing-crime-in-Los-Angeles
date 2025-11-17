# Analyzing Crime in Los Angeles

This project explores the `crimes.csv` dataset to analyze and uncover crime patterns in Los Angeles. The analysis, including feature engineering, and aggregation is contained within the `notebook.ipynb` file.

## Dataset

The primary dataset used is `crimes.csv`, which contains police report data for crimes in Los Angeles.

**Key columns include:**

* `DR_NO`: Division of Records Number (unique ID for the report)
* `Date Rptd`: Date the crime was reported
* `DATE OCC`: Date the crime occurred
* `TIME OCC`: Time the crime occurred
* `AREA NAME`: The name of the LAPD Area where the crime occurred
* `Crm Cd Desc`: Description of the crime
* `Vict Age`: Victim's age
* `Vict Sex`: Victim's sex
* `Vict Descent`: Victim's descent/ethnicity
* `Weapon Desc`: Description of the weapon used, if any
* `Status Desc`: Status of the case (e.g., "Invest Cont")
* `LOCATION`: Street address of the crime

## Tools and Technologies

* **Python**
* **pandas:** For data loading, cleaning, and manipulation.

## Project Workflow

The analysis in `notebook.ipynb` follows these key steps:

1. **Data Loading:** The `crimes.csv` file is loaded into a pandas DataFrame.
2. **Feature Engineering:**
    * The `DATE OCC` column is used to create new column (`h`) hour of crime occurence.
<!-- 3.  **Data Visualization & Analysis:** Several key analyses are performed and plotted:
    * A bar chart of the **Top 10 Most Common Crimes** (based on `Crm Cd Desc`).
    * A line plot showing **Crime Trends Over Time** (by `Year`).
    * A count plot illustrating the **Distribution of Crimes by LAPD Area** (using `AREA NAME`).
    * A pie chart visualizing **Victim Demographics by Sex** (`Vict Sex`).
    * A line plot showing the **Frequency of Crimes by Hour of the Day**. -->

## Files in this Repository

* `notebook.ipynb`: The Jupyter Notebook containing all the Python code, analysis, and visualizations.
* `crimes.csv`: The raw crime dataset.
* `README.md`: This file.

## How to Use

### Option 1: Direct Colab Link (Simplest)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ahmed-M0rsy/Analyzing-crime-in-Los-Angeles/blob/main/notebook.ipynb)

### Option 2: Get a local copy up and running, follow these simple steps

1. Clone this repository.
2. Install the required Python libraries: `pandas`.
3. Open and run the `notebook.ipynb` file in a Jupyter environment (like Jupyter Lab, Jupyter Notebook, or VS Code).
