# StackOverflow2024

## Projectdescription
this Project is about a datascience project which analyzes the StackOverflow surveys over the last 7 years (2024-2017). Therefore the goal of this Project is to analyze the follwing 3 main questions:

1. Do developers who frequently visit Stack Overflow report higher job satisfaction?
2. How does the usage of AI tools correlate with developers' concerns about AI's ethical implications and potential threats?
3. What is the relationship between years of professional coding experience and total compensation across different countries?

To answer these questions we will follow the CRISP-DM-Process. which contains of the following steps:
- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment

### Raw Data Structure
The raw data consists of a survey schema and the survey results. We got information from every year from 2017 to 2024. Before we can solve the questions written above we have to prepare the data. Therefore it is crucial to get them in the same schema for every year. the process for this task is described in the data preparation notebook (`notebooks/DataPreparation.ipynb`). The Prepared data will be stored in the folder `data/processed`

## Directory Structure

- `data/`: Contains the data used in the project.
- `notebooks/`: Jupyter notebooks for exploratory analyses.
- `src/`: Contains the project's source code.
- `tests/`: Test cases and unit tests.
- `requirements.txt`: List of Python packages required for the project.

## Installation
```bash
pip install -r requirements.txt