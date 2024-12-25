# Statistical Data Analyzer

## Overview
The **Statistical Data Analyzer** is a Python-based application designed for quick and efficient statistical analysis of datasets. It provides users with tools for descriptive statistics, data visualization, hypothesis testing, and correlation analysis. The tool is user-friendly and accessible through a command-line interface.

## Features
1. **Dataset Summary:**
   - Provides an overview of the dataset structure, including column types and missing values.
   - Generates descriptive statistics (mean, median, standard deviation, etc.).

2. **Data Visualization:**
   - Visualize the distribution of data in individual columns using histograms and density plots.

3. **Hypothesis Testing:**
   - Perform one-sample t-tests to evaluate if the mean of a column differs from a specified value.

4. **Correlation Analysis:**
   - Generate a heatmap to visualize correlations between numerical variables.

## How to Use
### Prerequisites
- Python 3.6 or higher
- Required libraries: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/StatisticalDataAnalyzer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd StatisticalDataAnalyzer
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
1. Run the script:
   ```bash
   python statistical_data_analyzer.py
   ```
2. Follow the prompts to:
   - Load your dataset (CSV format).
   - Perform desired analyses (e.g., summary, visualizations, tests).

### Example Usage
#### Input
```text
Enter the path to your CSV file: data.csv

Options:
1. Display dataset summary
2. Visualize data distribution
3. Perform hypothesis test
4. Visualize correlation matrix
5. Exit
Enter your choice: 1
```
#### Output
```text
--- Dataset Summary ---
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 100 entries, 0 to 99
Data columns (total 5 columns):
...

--- Descriptive Statistics ---
          Column1   Column2
mean       ...        ...
std        ...        ...
...
```

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature-name
   ```
4. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
- **Author:** [Your Name]
- **Email:** [Your Email]
- **GitHub:** [https://github.com/your-username](https://github.com/your-username)

## Future Enhancements
- Add support for additional statistical tests (e.g., ANOVA, chi-square).
- Include time series analysis features.
- Integrate with Jupyter Notebook for enhanced interactivity.

