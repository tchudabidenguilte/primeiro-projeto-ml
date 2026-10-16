# Primeiro Projeto de Machine Learning
# Brazilian Population Data Analysis 🇧🇷

## Overview

This project explores the population distribution across Brazilian municipalities using public data from the Brazilian Institute of Geography and Statistics (IBGE).

The analysis uses Python to clean, explore, summarize, and visualize population data from the 2022 Census.

## Objectives

- Load and prepare public demographic data.
- Perform exploratory data analysis (EDA).
- Identify the ten most populous municipalities.
- Calculate descriptive statistics.
- Communicate findings through visualizations.

## Technologies

- Python
- Pandas
- Matplotlib
- Requests
- Jupyter Notebook

## Data Source

**Source:** IBGE — Brazilian Institute of Geography and Statistics.

**Dataset:** SIDRA, Table 4709 — population indicators from the 2022 Census.

[Access the official IBGE dataset](https://sidra.ibge.gov.br/tabela/4709)

## Project Structure

- `notebooks/`: exploratory analysis.
- `data/`: input data, when stored locally.
- `figures/`: generated visualizations.
- `outputs/`: exported results.

## Methodology

1. Retrieve population data from the IBGE SIDRA API.
2. Inspect the dataset and its columns.
3. Clean missing, invalid, and duplicate records.
4. Calculate descriptive statistics.
5. Rank municipalities by population.
6. Generate and save a horizontal bar chart.
7. Interpret the results.

## Key Findings

- Number of municipalities analyzed: [insert result].
- Most populous municipality: [insert result].
- Median municipal population: [insert result].
- Main observation: [write a conclusion supported by your analysis].

## How to Run

Install the required packages:

```bash
python -m pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook notebooks/analise_populacao.ipynb
```

Run the notebook cells in order.

An internet connection is required to retrieve data from the SIDRA API.

## Limitations

This analysis describes the population data for the 2022 Census. It should not be interpreted as a current population estimate or as evidence of population growth.

## Author

Tchuda Bidenguilté

Physics graduate | MSc student at UTFPR | Python and Data Analysis

[GitHub Profile](https://github.com/Oneboy97)

## License

This project is intended for educational and portfolio purposes. Refer to IBGE's official documentation for data attribution and reuse conditions.
