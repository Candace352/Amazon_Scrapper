# Amazon Product Analysis

This repository contains Python code to fetch data from the Amazon website using the Rainforest API, analyze the product data, and visualize it using Matplotlib.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the required Python libraries installed (`requests`, `json`, `csv`, `pandas`, `matplotlib`).

## Usage

The main script `amazon_product_analysis.py` fetches product data from Amazon using the Rainforest API, creates a CSV file with the extracted data, and then visualizes the data using histograms and scatter plots.

## Requirements

- Python 3
- Required Python libraries (`requests`, `json`, `csv`, `pandas`, `matplotlib`)
- Rainforest API key (replace `'api_key': '4B5C506FF9D84D679CC5334794EEEBEA'` with your API key)

## Functionality

- **Data Retrieval**: Fetches product data from the Amazon website using the Rainforest API.
- **Data Processing**: Extracts relevant information such as product title, price, and rating from the API response.
- **CSV Creation**: Creates a CSV file (`response.csv`) containing the extracted data.
- **Data Visualization**: Generates histograms and scatter plots to visualize the distribution of prices and their relationship with ratings.

## Results

- **Histogram**: Shows the distribution of prices for the products fetched from Amazon.
- **Scatter Plot**: Illustrates the relationship between product prices and ratings.

