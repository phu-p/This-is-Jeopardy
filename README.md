# Jeopardy Data Analysis Project

## Overview

This project involves analyzing a dataset of Jeopardy! questions and answers. The goal is to filter the dataset for specific topics, compute the average difficulty of questions, and explore various insights to become a Jeopardy champion!

## Project Goals

- Load and clean the Jeopardy dataset.
- Filter questions based on specific keywords.
- Calculate the average value of questions to determine difficulty.
- Identify unique answers and their frequency.
- Explore additional insights, such as trends over time and category analysis.

## Dataset

The dataset used in this project is `jeopardy.csv`, which contains raw data from the Jeopardy game show. The columns include:

- `Show Number`
- `Air Date`
- `Round`
- `Category`
- `Value`
- `Question`
- `Answer`

## Key Features

- **Data Cleaning**: Remove extra spaces from column names for easier data manipulation.
- **Filtering Function**: A function to filter questions containing specific words.
- **Value Conversion**: Convert question values from strings to floats for analysis.
- **Unique Answers**: Identify and count unique answers to questions.
- **Exploratory Analysis**: Investigate trends and patterns in the dataset.

## Setup Instructions

1. Clone the repository to your local machine.
2. Ensure you have Python and pandas installed.
3. Run the Jupyter Notebook or Python script to execute the analysis.

## Usage

- Modify the filtering function to explore different topics.
- Use the analysis functions to gain insights into question difficulty and trends.
- Extend the project by exploring additional columns and creating new visualizations.
