# Board Game Data Scraper and Processor

This project is a Python-based web scraper and data processor for board game information from BoardGameGeek (BGG). It collects and processes data about board games, including average player ratings, player counts, and game weight, and prepares it for analysis or presentation.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Acknowledgements](#acknowledgements)

## General Information

This project aims to solve the problem of collecting detailed board game data from BGG and processing it for further analysis. It was undertaken to provide board game enthusiasts and researchers with easy access to comprehensive game information.

## Technologies Used

- Python 3.8
- Pandas 1.5.3
- BeautifulSoup (bs4) 4.11.2
- urllib
- re (Regular Expressions)
- JSON
- shutil
- os

## Features

- Scrapes board game data from BGG.
- Extracts statistics data, including average player ratings.
- Extracts player count data (minimum and maximum players).
- Extracts game weight data.
- Converts object-type columns in a DataFrame to numeric data types (float or int).
- Prepares a DataFrame from a dictionary of game data.
- Converts and replaces decimal separators in numeric columns for Google Sheets compatibility.

## Setup

To run this project, you need Python 3.8 or later. Clone the repository and install the required libraries:

```bash
pip install pandas beautifulsoup4
```
## Usage
To use this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required libraries (see the Setup section).
3. Set your data in Setting section
BGG_USER_COLLECTION_URL = _URL TO COLLECTION THAT WANT TO SCRAPED DATA_
CSV_DESTINATION_PATH = _DESTINATION WHERE YOUR CSV FILE SHOULD BE SAVED_
4. Run the Python scripts to scrape and process board game data.
5. Customize the scripts and functions according to your requirements.

## Project Status
The project is complete and actively maintained. Updates and improvements may be added in the future.

## Acknowledgements
This project was inspired by the need for accessible and well-structured board game data for analysis and research. Many thanks to the open-source community and contributors who make projects like this possible.
