# Hotel Booking Cancellation Analysis

An exploratory data analysis portfolio project using hotel booking records to examine cancellation patterns, average daily rate (ADR), hotel type, reservation timing, country, and market segment.

## Portfolio Summary

This project demonstrates a complete beginner-to-intermediate data analysis workflow in Python:

- Loaded and inspected booking-level data with pandas
- Converted reservation status dates into a usable datetime format
- Reviewed missing values, data types, descriptive statistics, and ADR outliers
- Compared cancellation patterns across hotel types, months, countries, and market segments
- Created charts with matplotlib and seaborn to communicate the analysis

## Tools and Skills

`Python` · `pandas` · `matplotlib` · `seaborn` · `Jupyter Notebook` · exploratory data analysis · data cleaning · data visualization

## Project Contents

- `csv_analysis.ipynb` - the cleaned analysis notebook
- `hotel_bookings 2.csv` - the dataset used by the notebook
- `requirements.txt` - Python packages required to run the notebook

## Key Questions

- What proportion of bookings were cancelled?
- How do cancellation patterns differ between City Hotel and Resort Hotel?
- How does ADR vary over time and by cancellation status?
- Which countries and market segments appear most often among cancelled bookings?

## How to Run

1. Clone or download this repository.
2. Create and activate a Python environment.
3. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Open `csv_analysis.ipynb` in Jupyter Notebook or VS Code.
5. Run all cells from top to bottom.

The notebook expects the CSV file to remain in the same folder and uses the relative path `hotel_bookings 2.csv`.

## Dataset and Privacy

The included file contains booking-level hotel data and appears to contain no direct names, email addresses, phone numbers, or payment details. It does contain country, booking, reservation, and hotel-related fields.

The original dataset source and license are not recorded in the current project files. Before using this repository as a public portfolio project, verify that the dataset may be redistributed and add the source URL, dataset name, license, and attribution here. If redistribution is not permitted, remove the CSV from the repository and document how reviewers can obtain the data legally.

## Notes and Limitations

- This is descriptive exploratory analysis, not a causal study or a cancellation prediction model.
- The notebook filters records with `adr >= 5000` before plotting. The reason for this rule should be documented and justified with the dataset source or project brief.
- Results depend on the supplied CSV and the date parsing used in the notebook.
- The analysis should not be used to make operational decisions without validation against current hotel data.

## Project Title for Resume

**Hotel Booking Cancellation Analysis with Python**

Resume description:

> Performed exploratory analysis of hotel booking cancellations using Python, pandas, matplotlib, and seaborn; cleaned date fields, reviewed ADR outliers, and visualized cancellation patterns by hotel type, month, country, and market segment.
