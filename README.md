# Reservoir Data Analysis and Visualization

## Project Overview

This project involves the analysis and visualization of daily reservoir data from the Central Water Commission (CWC) during March 2024. The primary objectives are to clean and preprocess the data, visualize daily variations and correlations, and perform statistical analysis to gain insights into reservoir management and capacity utilization.

## Features

1. **Data Cleaning and Preprocessing**:
    - Handling missing data by imputing mean values for 'Storage' and 'Level' columns on a per-reservoir basis.

2. **Visualization of Reservoir Data**:
    - Line plots for daily variations in reservoir levels.
    - Scatter plots for storage vs. level correlations.
    - Bar plots for mean levels and storage across different reservoirs.
    - Box plots and violin plots for statistical summaries.
    - Joyplots for comparing distributions across multiple reservoirs.

3. **Statistical Analysis**:
    - Paired t-tests to assess significant differences between storage and level values for various reservoirs.
    - Interpretation of t-test results to understand reservoir capacity utilization.

## Technologies Used

- **Python**: For data analysis and manipulation using pandas and NumPy.
- **Seaborn and Matplotlib**: For creating detailed and informative visualizations.
- **SciPy**: For conducting statistical tests and analysis.
- **JoyPy**: For generating joyplots to compare distributions across multiple categories.

## Installation

To run this project, you need to have Python and the required libraries installed. You can install the required libraries using the following command:

```bash
pip install pandas seaborn matplotlib numpy scipy joypy
```

## Usage

1. **Data Cleaning and Preprocessing**:
    - The script reads the CSV file containing reservoir data.
    - Missing values in 'Storage' and 'Level' columns are replaced with the mean values for each reservoir.

2. **Visualization**:
    - Various plots are created to visualize the data and gain insights into reservoir levels and storage.

3. **Statistical Analysis**:
    - Paired t-tests are performed to check for significant differences between storage and level values.

To run the script, simply execute the Jupyter Notebook or Python script file provided in the repository.

## Results

The results of the analysis include:
- Visualizations showing daily variations and correlations in reservoir data.
- Statistical analysis highlighting significant differences between storage and level values.
- Insights into reservoir management and capacity utilization.

## Contributions

Contributions to this project are welcome. Please feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please contact [Karan Patel] at [karanp0608@gmail.com].
