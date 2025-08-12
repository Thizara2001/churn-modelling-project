
# Churn Modeling - Data Preprocessing Project

This project focuses on **data preprocessing** for churn modeling, specifically handling **missing values** in a customer dataset. The project also demonstrates an **exploratory data analysis (EDA)** process and uses an **AI-powered solution** for predicting missing gender values based on names.

## Project Overview

The goal of this project is to clean and preprocess the **ChurnModelling.csv** dataset, handle missing values, and create a clean dataset that is ready for machine learning modeling. The missing data is handled through **imputation** and **AI-based gender prediction** using **Groq’s LLaMA 3.3 LLM** model.

### Features of the Project:
- **Handled Missing Values**: Missing values are imputed for both numerical and categorical columns.
- **AI-Powered Gender Prediction**: The missing gender data is predicted using **Groq’s LLaMA 3.3 LLM** based on first and last names.
- **Exploratory Data Analysis (EDA)**: The dataset is explored to check for missing values, distributions, and relationships.
- **Tech Stack**:
    - Python
    - Pandas
    - Seaborn
    - Pydantic
    - Jupyter Notebooks
    - Groq’s LLaMA 3.3 LLM API

## Project Structure

/WEK 01
│
├── data/
│ ├── processed/
│ │ └── ChurnModelling_Missing_Values_Handled.csv
│ └── raw/
│ └── ChurnModelling.csv
│
├── .env
├── 0_handle_missing_values.ipynb
├── requirements.txt
└── README.md


### Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-modelling-project.git
   cd churn-modelling-project

    Install dependencies:

pip install -r requirements.txt

Create a .env file to store your environment variables (e.g., API keys for Groq). The .env file should look like:

GROQ_API_KEY=your-api-key-here

Run the Jupyter notebook:

    jupyter notebook 0_handle_missing_values.ipynb

Data Files

    raw/ChurnModelling.csv: The original raw customer churn dataset.

    processed/ChurnModelling_Missing_Values_Handled.csv: The cleaned and processed dataset after handling missing values.

Contributions

Feel free to fork this project, make changes, and submit pull requests. Any suggestions or improvements are welcome!