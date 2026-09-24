# Hotel Booking Cancellation Analysis

A beginner-friendly exploratory data analysis project using hotel booking records. The notebook examines cancellation rates, average daily rate (ADR), hotel type, reservation timing, country, and market segment.

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

The included file contains booking-level hotel data and appears to contain no direct names, email addresses, phone numbers, or payment details. It does contain country, booking, reservation, and hotel-related fields. Confirm that redistribution is allowed under the dataset's original license before publishing the CSV.

The original dataset source and license are not recorded in this project. Add the verified source URL, dataset name, license, and attribution here before uploading to GitHub. Do not claim that the data is public or reusable until this is confirmed.

## Notes and Limitations

- This is descriptive exploratory analysis, not a causal study or a cancellation prediction model.
- The notebook filters records with `adr >= 5000` before plotting. The reason for this rule should be documented and justified with the dataset source or project brief.
- Results depend on the supplied CSV and the date parsing used in the notebook.
- The analysis should not be used to make operational decisions without validation against current hotel data.

## Suggested Project Title

**Hotel Booking Cancellation Analysis with Python**

This title is specific, searchable, and accurately describes the work without overstating the result.
