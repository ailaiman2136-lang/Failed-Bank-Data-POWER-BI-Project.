# Failed Bank Analysis | Power BI

An interactive Power BI report exploring U.S. bank failures using publicly available data from the Federal Deposit Insurance Corporation (FDIC).

The report helps users examine where and when bank failures occurred and compare results across states and years.

## Before and After

### Before: Source Data
![Source data before transformation](imagesbefore-source-data.png)


### After: Power BI Report
![Completed Power BI report](imagesafter-power-bi-report.png)

## Project Goals

- Connect Power BI to a public FDIC failed-bank data source.
- Clean and prepare the data with Power Query.
- Create a calendar table for date-based analysis.
- Explore bank failures by state and time.
- Present findings in an interactive report.

## Tools and Skills

- Power BI Desktop
- Power Query
- DAX
- Data cleaning and transformation
- Data modeling
- Report design and data visualization

## Data Source

The report uses the FDIC’s public **Failed Bank List**.

- Source: [FDIC Failed Bank List](https://www.fdic.gov/resources/resolutions/bank-failures/failed-bank-list/)
- Data provider: Federal Deposit Insurance Corporation (FDIC)

The FDIC may update its data over time. Report results can change when the source data changes.

## Report Features

- Bank failure counts by state
- Date-based analysis using a calendar table
- Interactive visuals and filtering
- A combined city-and-state field to distinguish locations with the same city name

> Update this section to match the visuals and features in your finished report.

## Project Workflow

1. Connected Power BI to the FDIC data.
2. Used Power Query to rename the query and remove unneeded columns.
3. Created a combined city-and-state column.
4. Loaded the prepared data into the Power BI model.
5. Created a calendar table and date-related fields.
6. Built report visuals to explore the data.
7. Published the report to the Power BI service, if available.

## Repository Structure

```text
.
├── images/
│   ├── before-source-data.png
│   └── after-power-bi-report.png
├── Failed-Bank-Analysis.pbix
├── Failed-Bank-Data-CVS.pbix
└── README.md
```
##  Notes

Power BI Desktop is needed to open the .pbix file.

The report connects to a public web data source, so access or refresh may depend on your network settings.

This project is for learning and analysis. It should not be treated as financial advice.

## Acknowledgments
This project was created as a learning exercise based on the Power BI Beginner to Pro tutorial by Pragmatic Works.

## Author
[AILA IMAN]
