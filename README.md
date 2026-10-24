# Netflix-Data-Cleaning-Preparation
Netflix data cleaning and preparation using Python and Pandas
# Netflix Data Cleaning & Preparation

## Project Overview
This project focuses on cleaning and preparing a Netflix dataset using Python and Pandas. The goal is to improve data quality and organize the data for future analysis and business reporting.

## Project Objectives
- Inspect the dataset and its structure.
- Identify missing values, blank cells, and duplicate records.
- Detect placeholder values.
- Standardize column names and text formatting.
- Convert `date_added` into a datetime format.
- Validate duration formats and unique show IDs.
- Export the cleaned dataset to CSV.

## Tools & Technologies
- Python
- Pandas
- Google Colab
- CSV

## Dataset Information
The dataset contains **8,790 rows and 10 columns**.

| Column | Description |
|---|---|
| `show_id` | Unique identifier for each title |
| `type` | Movie or TV Show |
| `title` | Title of the content |
| `director` | Director's name |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating |
| `duration` | Movie runtime or number of seasons |
| `listed_in` | Genre and category information |

## Data Cleaning Process
1. Imported the dataset using Pandas.
2. Inspected rows, columns, data types, missing values, and duplicates.
3. Checked for blank cells and common placeholder values.
4. Standardized column names.
5. Removed leading and trailing spaces from text fields.
6. Converted `date_added` into datetime format.
7. Checked duration formatting and show ID uniqueness.
8. Exported the prepared dataset as a CSV file.

## Results
- **Total records:** 8,790
- **Total columns:** 10
- **Unique show IDs:** 8,790
- **Duplicate rows detected:** 0
- **Missing values reported in final validation:** 0
- **Unique country entries:** 86

**Data quality note:** One record contains `Unknown` as its title. This placeholder was identified for further review rather than automatically deleting the record.

##  Repository Files
- `Netflix_Data_Cleaning_&_Preparation_.ipynb` — Notebook containing the Python code and outputs.
- `netflix_cleaned.csv` — Exported cleaned dataset.
- `README.md` — Project documentation.

##  How to Run
1. Open the notebook in Google Colab.
2. Upload the original Netflix CSV dataset when prompted.
3. Run the notebook cells in order.
4. Review the cleaning and validation results.
5. Export the cleaned dataset.

## Future Improvements
- Perform exploratory data analysis (EDA).
- Visualize movies versus TV Shows.
- Analyze ratings, countries, and release years.
- Build a dashboard for business reporting.

## Author
**Mansi**

*Python | Pandas | Data Cleaning | Data Analytics*
