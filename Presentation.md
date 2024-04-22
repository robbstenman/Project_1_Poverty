# Slides

## Overview of data collection

- The goal of our data window was for the years 2011-2021
- Data was collected from the following sources:
  - [U.S. Census Bureau](https://www.census.gov/)
  - [Point in Time (PIT) Data](https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/)
  - [Homeless Students](https://www.cde.state.co.us/studentsupport/homeless_data)
  - [SNAP Data](https://fred.stlouisfed.org/series/BRCO08M647NCEN)
  - [Self-Sufficiency Standard](https://selfsufficiencystandard.org/colorado/)
- Some data was retrieved using the Census API
  - We had to collect data for each county and year separately
  - County data was retrieved using FIPS codes
  - Allowed us to do comparisons between counties with the lowest & highest populations and the state
- Other data was imported from CSV and Excel files

## Data Cleaning

- Data was cleaned using Python and Pandas
- Some data was cleaned using Excel to remove unnecessary sheets and to format the data
- Data was exported to a CSV file

## Approach our group took in achieving project goals

- We divided the work into tasks and assigned them to each team member
- We met regularly to discuss progress and issues
- We used Slack, GitHub, and Google Drive to communicate and share files
- We used Jupyter Notebook to write and test our code
- We used matplotlib to create visualizations
