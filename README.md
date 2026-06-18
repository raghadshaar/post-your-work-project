# US Bikeshare Data Exploration Project

## Date Created
June 18, 2026

## Overview
This Python project explores bikeshare data for three U.S. cities:

- Chicago
- New York City
- Washington

Users can filter data by city, month, and day of the week, then view statistics about travel patterns, stations, trip durations, and user demographics.

## Requirements

- Python 3.x
- Pandas
- NumPy

Install dependencies:

```bash
pip install pandas numpy
```

## Files

```text
bikeshare_starter.py
chicago.csv
new_york_city.csv
washington.csv
README.md
```

## Running the Program

```bash
python bikeshare_starter.py
```

Follow the prompts to select:

- City (`chicago`, `new york city`, `washington`)
- Month (`all`, `january`–`june`)
- Day (`all`, `monday`–`sunday`)

## Statistics Available

- Most common travel times
- Most popular stations and routes
- Total and average trip duration
- User type counts
- Gender and birth year statistics (when available)

## Known Issue

`washington.csv` does not contain Gender or Birth Year data, so those statistics are skipped for Washington.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Motivate for the bikeshare datasets
- Pandas and NumPy documentation
- Udacity Data Analyst Nanodegree Program