# Student Performance Analysis

##  Overview

This project analyses a synthetic student performance dataset using **Python**, **Pandas**, **NumPy**, and **Matplotlib** in a **Jupyter Notebook** environment.

The notebook simulates a simple end-to-end data analysis workflow by generating student test scores for **Math**, **Science**, and **English**, exporting the data to CSV, and then performing cleaning checks, descriptive analysis, visualisation, correlation analysis, and outlier detection.

---

##  Objective

To explore student performance data and identify patterns in score distribution, variability, subject relationships, and potential outliers.

---

##  Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy

---

## Dataset

The dataset was **generated programmatically** within the notebook using NumPy random integers.

### Dataset details
- **1,000 student records**
- **3 subjects**
  - Math
  - Science
  - English
- Score range:
  - **0 to 100**

The dataset is exported as:

```text
student_performance.csv

1. Data Generation

Generated 1,000 random scores for Math, Science, and English
Created a structured DataFrame
Exported the dataset to CSV
2. Data Loading

Read the generated CSV file into Pandas
Converted the dataset into a NumPy array for further analysis

3. Data Quality Checks
Checked for missing values
Reviewed data types for each column

4. Descriptive Statistics

Calculated the following for each subject:

Mean
Median
Mode
Range
Variance
Standard deviation

5. Visualisation

Created:

Histograms for each subject
Boxplot comparing score distributions across subjects
6. Correlation Analysis
Calculated the correlation matrix between Math, Science, and English scores
Assessed whether performance in one subject related to performance in another

7. Outlier Detection
Applied Z-score analysis
Identified whether any extreme values were present

Key Findings
The score distributions are wide and fairly even across all three subjects.
The average scores are close to the midpoint of the 0–100 range.
Science shows the highest variance in the notebook output, indicating the greatest spread in scores.
Correlation values between subjects are very low, suggesting little to no strong relationship between subject performance.
No significant outliers were detected using the Z-score threshold.

Visual Outputs

The notebook includes:

Subject score histograms
Comparative boxplot
Correlation matrix output
Summary interpretation of results

Skills Demonstrated
Generating synthetic datasets with NumPy
Creating and manipulating DataFrames with Pandas
Performing descriptive statistical analysis
Visualising distributions with Matplotlib
Conducting correlation analysis
Detecting outliers using Z-scores
Summarising analytical findings in a notebook workflow

Limitations
The dataset is synthetic rather than real-world data.
Scores are randomly generated, so observed patterns are illustrative rather than naturally occurring.
Correlation and outlier results are specific to the generated sample.

Future Improvements
Use a real educational dataset
Add subject-level pass/fail analysis
Segment students into performance bands
Build comparative visualisations by score category
Extend the project with predictive modelling

Conclusion

This project demonstrates a beginner-friendly Python data analysis workflow using a generated student performance dataset. It shows the ability to create data, validate it, analyse statistical properties, visualise results, and summarise findings clearly in Jupyter Notebook.
