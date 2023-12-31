# Data Analysis on [Jumia](https://jumia.co.ke)

## Overview

This repository contains a Jupyter Notebook (`analysis.ipynb`) and a dataset (`smartphones.csv`) for a comprehensive data analysis on [Jumia](https://jumia.co.ke), focusing on smartphone products. The analysis aims to uncover insights into various aspects of the smartphone offerings, including pricing, product features, customer reviews, and brand performance.

## Files

- **[analysis.ipynb](analysis.ipynb)**: Jupyter Notebook containing the code and visualizations for the data analysis.
- **[smartphones.csv](smartphones.csv)**: CSV file containing the dataset used for the analysis.

## Analysis Highlights

- **Data Exploration**: The Jupyter Notebook explores the dataset, providing insights into key features such as pricing, RAM and ROM, battery, display sizes, and customer reviews.

- **Visualizations**: Various visualizations, including histograms, scatter plots, and radar charts, are utilized to present a clear understanding of the data.

- **Brand Performance**: The analysis delves into the performance of different smartphone brands, highlighting key metrics such as average ratings, pricing and so forth.


## Dependencies

The analysis is built using Python and Jupyter Notebook, relying on the libraries below:

- **BeautifulSoup (bs4)**: A library for web scraping and parsing HTML or XML documents.
- **pandas**: A data manipulation and analysis library, used for handling and processing tabular data.
- **numpy**: A library for numerical operations in Python, essential for efficient data handling.
- **matplotlib**: A 2D plotting library for creating static, animated, and interactive visualizations.
- **seaborn**: A data visualization library based on matplotlib, providing additional functionality and improved aesthetics.
- **textblob**: A library for processing textual data, including sentiment analysis using the Naive Bayes classifier.

To install these dependencies along with Jupyter, you can use the following command:

```bash
pip install jupyter bs4 pandas numpy matplotlib seaborn
```
## Usage

```bash
git clone https://github.com/alvinmurimi/jumia.git
cd jumia
jupyter notebook analysis.ipynb
