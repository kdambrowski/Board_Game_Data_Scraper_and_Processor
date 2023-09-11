# Board Game Data Scraper and Processor

This project is a Python-based web scraper and data processor for board game information from BoardGameGeek (BGG). It collects and processes data about board games, including average player ratings, player counts, and game weight, and prepares it for analysis or presentation.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information

This project aims to solve the problem of collecting detailed board game data from BGG and processing it for further analysis. It was undertaken to provide board game enthusiasts and researchers with easy access to comprehensive game information.

## Technologies Used

- Python 3.8
- Pandas
- BeautifulSoup (bs4)
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

## Screenshots

[Include screenshots or visual aids if applicable.]

## Setup

To run this project, you need Python 3.8 or later. Clone the repository and install the required libraries:

```bash
pip install pandas beautifulsoup4
