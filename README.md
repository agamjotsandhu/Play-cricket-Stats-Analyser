# Play-cricket-Stats-Analyser
Cricket Stats Scraper

Overview

This project is a web scraper designed to extract batting and bowling statistics from cricket websites. Using Selenium, the program navigates the site, retrieves data, and organizes it into a structured format for analysis. The statistics are then saved in a CSV file for further use.

Motivation
I created this tool to automate the process of gathering cricket stats, making it easier to analyze player and team performances without manually copying and pasting data. This script is especially useful for cricket analysts, players, and enthusiasts who want quick insights into batting and bowling performances.

Features
  Scrapes batting and bowling statistics from cricket websites.
  Saves the extracted data into a structured Pandas DataFrame.
  Offers an option to save the data as a CSV file.
  Performs basic statistical analysis, including total runs, wickets, and averages per team.

Dependencies
  Selenium
  Numpy
  Pandas

How It Works
  The script prompts the user to enter a valid PlayCricket competition stats URL.
  The user selects whether they want batting or bowling statistics.
  Selenium opens the webpage and navigates to the stats tab.
  The script extracts relevant data, formats it, and stores it in a Pandas DataFrame.
  The user is given the option to save the data as a CSV file.
  The script performs a basic analysis of the stats, displaying team-wise averages and totals.

Usage
  Run the script
  When prompted, enter the cricket stats webpage link and select whether you want batting or bowling stats.
  
Potential Improvements
  Implementing error handling for missing data or incorrect webpage structures.
  Adding support for multiple cricket websites.
  Enhancing the analysis with more advanced statistics and visualizations.
  Running Selenium in headless mode for improved efficiency.
  Bowling stats have first couple team names wrong (cannot figure out why)

License
This project is open-source and available under the MIT License.

