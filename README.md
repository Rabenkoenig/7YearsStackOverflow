# StackOverflow2024

## Project Description
This project is a data science analysis of the Stack Overflow Developer Surveys from 2017 to 2024. The goal is to answer the following three main questions:

1. Do developers who frequently visit Stack Overflow report higher job satisfaction?
2. How does the usage of AI tools correlate with developers' concerns about AI's potential threats?
3. What is the relationship between years of professional coding experience and total compensation across different countries?

The project follows the CRISP-DM process, which consists of:
- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment

### Motivation
The motivation behind this project is to explore trends and relationships within the developer community in the year 2024, with a particular focus on job satisfaction, AI tools usage, and the global developer compensation landscape.

### Libraries Used
This project utilizes the following Python libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `scikit-learn`: For machine learning models.
- `matplotlib` and `seaborn`: For data visualization.
- `statsmodels`: For regression analysis and statistical testing.
- `jupyter`: For creating and running notebooks.

### Data Structure
The raw data comes from the Stack Overflow Developer Surveys for each year from 2017 to 2024. To answer the research questions, the data was cleaned, unified, and prepared for analysis. Details of the data preparation process can be found in the `notebooks/DataPreparation.ipynb` file. The processed data is stored in the `data/processed` folder.

## Directory Structure
The project files are organized as follows:

- `data/`: Contains the raw and processed data used in the project.
  - `raw/`: The original survey data files.
  - `processed/`: Cleaned and prepared data files used for analysis.
- `notebooks/`: Contains the Jupyter notebooks for data exploration and modeling.
  - `analysis_01_job_satisfaction.ipynb`
  - `analysis_02_ai_usage_ethics.ipynb`
  - `analysis_03_education_self_learning.ipynb`
- `README.md`: The current document, describing the project, its structure, and results.
- `requirements.txt`: A list of all necessary libraries used in the project.

## Acknowledgements
The data used in this project is sourced from Stack Overflow's Developer Survey, available [here](https://cdn.sanity.io/files/jo7n4k8s/production/262f04c41d99fea692e0125c342e446782233fe4.zip/stack-overflow-developer-survey-2024.zip). This project was developed as part of a data science course, following best practices for reproducibility. Special thanks to the tutors of udacity, including StackOverflow and Kaggle, for providing invaluable references during the project.

