# SEGA Games
SEGA Games Dataset (Kaggle) analysis

![SEGA logo](/Codes/segalogo.jpeg)

Welcome to the SEGA Games repository! This repository contains comprehensive data analysis and predictive modeling related to SEGA games. It is designed to provide insights into the world of SEGA gaming, including the exploration of historical data and the development of predictive models for game scores and ratings.

## Table of Contents

1. [Dataset](#1-dataset)
2. [Exploratory Data Analysis (EDA) & Analysis](#2-exploratory-data-analysis-eda--analysis)
3. [Predictive Models](#3-predictive-models)
4. [Installation](#4-installation)
5. [Usage](#5-usage)
6. [Contributing](#6-contributing)
7. [License](#7-license)
8. [Clone this Repository](#Clone-this-Repository)

## 1. Dataset

### Overview

- **Source**: [SEGA Games Dataset on Kaggle](https://www.kaggle.com/datasets/joebeachcapital/sega-games)
- **Description**: This dataset consists of all Sega games for all platforms, scraped from metacritic.com as of August 24, 2023. It includes the following columns:

  - **meta score**: Meta score of the game.
  - **user score**: User score of the game.
  - **title**: Title of the game.
  - **platform**: Platform(s) on which the game is available.
  - **release date**: Release date of the game.
  - **details page link**: Link to the details page of the game.
  - **esrb rating**: ESRB (Entertainment Software Rating Board) rating of the game.
  - **developers**: Developers of the game.
  - **genres**: Genres to which the game belongs.

This dataset serves as the foundation for the analyses and predictive models presented in this repository.

## 2. Exploratory Data Analysis (EDA) & Analysis

- **File**: `EDA&Analysis.ipynb`

In this section, I delve into the rich dataset of SEGA games to uncover valuable insights and trends. The EDA and Analysis notebook (`EDA&Analysis.ipynb`) covers the following key areas:

### Frequency Distribution of Genres
I start by examining the distribution of game genres, providing an overview of the most popular genres within the SEGA gaming universe.

### Genres vs. Meta Scores Analysis
I analyze how different genres correlate with Meta Scores, shedding light on which genres tend to receive higher or lower ratings from critics.

### ESRB Rating vs. Scores
I explore the relationship between ESRB ratings and game scores, helping us understand how ratings influence game quality.

### Release Date vs. Scores
A time series analysis is conducted to visualize how game scores have evolved over time, offering insights into trends within the SEGA gaming landscape.

### Correlation Analysis
I calculate and discuss the correlation between Meta Scores and User Scores, providing an understanding of the alignment between critics' and users' opinions.

## 3. Predictive Models

- **File**: `Models.ipynb`

In this section, I venture into predictive modeling, aiming to forecast game scores and ratings. The Predictive Models notebook (`Models.ipynb`) includes the following components:

### Data Preprocessing
I begin by preparing the data for modeling, addressing issues such as missing values and data type conversions to ensure data quality.

### Feature Engineering
Effective feature engineering is crucial. I select and engineer features that significantly impact the performance of predictive models.

### Meta Score Prediction
I construct models to predict Meta Scores, providing insights into how games are likely to be reviewed by professional critics.

### User Score Prediction
I develop models to predict User Scores, reflecting the opinions of gamers themselves.

### Interpretation and Insights
I interpret the results and derive insights into the factors influencing game scores, using visualization tools to convey these findings effectively.

## 4. Installation

To run the notebooks and experiments in this repository, you need to install the required Python libraries. You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```
## 5. Usage

To explore the analyses, insights, and predictive models, you can access the respective Jupyter Notebook files: `EDA&Analysis.ipynb` and `Models.ipynb`. Feel free to run the code and experiment with the data to gain a deeper understanding of SEGA games.

## 6. Contributing

I welcome contributions! If you have additional data, insights, or improvements to the analysis and models, please submit a pull request. Your contributions will help enhance the quality of this repository.

## 7. License

This repository is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code and contents as long as you provide appropriate attribution and adhere to the terms of the license.

For any questions or inquiries, feel free to contact me.

## Clone this Repository

To clone this repository to your local machine, use the following command:

```bash
git clone https://github.com/hossein-zandinejad/SEGA-Games.git
```

Enjoy exploring the world of SEGA games!
