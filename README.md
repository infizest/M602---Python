# Carbon Footprint Monitoring Tool

## Overview
This Python-based Carbon Footprint Monitoring Tool analyzes and visualizes CO2 emissions for different countries and years based on the **OWID CO2 dataset**. It allows users to generate reports and trends by selecting a country and year interactively.

## Features
- Displays **available countries and years** before taking user input.
- Generates **CO2 emissions reports** in CSV format.
- Plots **trends of CO2 emissions over time**.
- Handles **invalid inputs** gracefully.

## Requirements
Ensure you have the following dependencies installed:
- **Python 3.x**
- **pandas** (for data handling)
- **openpyxl** (for reading Excel files)
- **matplotlib** (for visualizations)

You can install the required packages using:
```bash
pip install pandas openpyxl matplotlib
```

## Running the Script in Google Colab
1. **Upload the dataset** (`owid-co2-data.xlsx`) to Google Colab.
2. **Run the following command** to install dependencies:
   ```python
   !pip install pandas openpyxl matplotlib
   ```
3. **Execute the script** step by step to:
   - Load the dataset.
   - Select a country and year interactively.
   - Generate a CO2 report.
   - Visualize emission trends.

## Example Usage
```python
# Run the script
python carbon_footprint_tool.py
```

## Output
- A **carbon footprint report** saved as `carbon_report_COUNTRY_YEAR.csv`.
- A **graph showing CO2 emission trends**.

## Notes
- Ensure the dataset **owid-co2-data.xlsx** is available in the correct path.
- If running in **Google Colab**, you may need to re-upload the dataset every session.
- Modify the dataset path in the script if necessary.

## Author
Developed as part of **M602 Computer Programming** coursework at **GISMA University of Applied Sciences**.

