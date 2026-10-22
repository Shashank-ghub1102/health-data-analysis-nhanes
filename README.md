# NHANES Health Data Analysis

An exploratory statistics and visualisation project comparing adult male and female body-measurement data using Python, NumPy, pandas, SciPy, and Matplotlib.

## Project overview

The analysis works with seven anthropometric measurements, including weight, height, limb lengths, and body circumferences. It explores distributions, compares summary statistics, and derives additional measurements such as body mass index (BMI).

## What it covers

- Loading tabular measurements with pandas and converting data to NumPy arrays
- Comparing body-weight distributions with histograms and box plots
- Calculating descriptive statistics such as mean, median, standard deviation, skewness, and kurtosis
- Deriving BMI from weight and height
- Visualising and exploring relationships in body-measurement data

## Repository contents

- `corizo_capstone_1_final (1).py` — analysis script exported from Google Colab
- `health-data-analysis-nhanes project.pdf` — project report

## Requirements

- Python 3.10 or newer recommended
- NumPy
- pandas
- Matplotlib
- SciPy

Install the Python dependencies:

```bash
python -m pip install numpy pandas matplotlib scipy
```

## Data and running the analysis

The script currently expects two CSV files—one for adult male measurements and one for adult female measurements—to be available in a Google Drive folder. It uses Google Colab's `google.colab.drive` module and hard-coded paths under `/content/drive/MyDrive/Colab Notebooks/csv files/`.

1. Open the script in Google Colab or adapt it for your local Python environment.
2. Obtain the source CSV files from the dataset source referenced in the project report.
3. If using Colab, upload the CSV files to the expected Drive folder or update the paths in the script.
4. Install the dependencies above if they are not already available.
5. Run the cells/script and review the generated plots and statistical summaries.

The dataset CSVs are not included in this repository, so the analysis will not run end-to-end until those files are supplied and the paths are configured.

## Important note

This is an educational exploratory analysis, not a clinical tool. Group-level patterns should not be interpreted as medical advice or as conclusions about every individual in either group.
