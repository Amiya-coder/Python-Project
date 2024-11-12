# 2022 T20 World Cup Data Analysis

This Python project performs data analysis on the 2022 T20 World Cup using datasets related to the tournament. The analysis aims to uncover trends, insights, and patterns in the performance of teams and players throughout the competition.

## Project Overview

This project processes and analyzes various datasets of the 2022 T20 World Cup to generate meaningful insights. The analysis includes examining batting and bowling performance, match results, player statistics, and more. This project is organized into three main Python scripts that modularize the functionality.

### Key Features:
- Analysis of match results and team performance.
- Insights into individual player statistics (batting, bowling, etc.).
- Visualizations of performance trends throughout the tournament.
  
## Project Structure

The project consists of the following files:

- **dataloader.py**: A module for loading and cleaning the dataset, preparing it for analysis. This includes reading match and player data, handling missing values, and converting necessary data formats.
- **myModule.py**: Contains various utility functions for performing specific analyses on the dataset. For example, functions to calculate batting averages, strike rates, economy rates, and more.
- **project.py**: The main script where the core data analysis and visualization are executed. This script ties together the functions from the other modules and produces the final output and insights.

### File Breakdown:
- **dataloader.py**: Functions for data cleaning and preprocessing (loading data from CSV, handling null values, etc.).
- **myModule.py**: Analysis functions for calculating statistics like batting averages, economy rates, etc.
- **project.py**: Main execution script that integrates all modules and generates outputs (statistics, plots, etc.).

## Requirements

To run this project, you'll need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn


