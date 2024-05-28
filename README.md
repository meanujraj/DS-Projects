# The Sales Analysis Project

## Overview

This project aims to analyze sales data from multiple CSV files to derive meaningful insights and answer key business questions. The analysis includes data cleaning, aggregation, and visualization to understand sales trends, top-performing products, optimal advertisement times, and more.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Analysis](#analysis)
  - [Best Month for Sales](#best-month-for-sales)
  - [City with Highest Sales](#city-with-highest-sales)
  - [Optimal Advertisement Time](#optimal-advertisement-time)
  - [Products Sold Together](#products-sold-together)
  - [Most Sold Products](#most-sold-products)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sales-analysis.git
    cd sales-analysis
    ```

2. Install the required packages:
    ```bash
    pip install pandas matplotlib
    ```

## Usage

1. Place all monthly sales data CSV files in the `Sales_Data` directory.
2. Run the analysis script:
    ```python
    python sales_analysis.py
    ```

## Data Cleaning

The data cleaning process includes:
- Dropping rows with NaN values.
- Removing invalid rows where the `Order Date` column contains non-date values.
- Converting data types of `Quantity Ordered` and `Price Each` columns to numeric.

## Analysis

### Best Month for Sales

Identifies the best month for sales by aggregating total sales for each month.

### City with Highest Sales

Determines which city had the highest sales by summing up the sales for each city.

### Optimal Advertisement Time

Finds the optimal time to display advertisements by analyzing order frequencies by hour.

### Products Sold Together

Identifies products that are most often sold together by analyzing orders with multiple products.

### Most Sold Products

Determines the most sold products and compares their quantities with the average price to understand their popularity.

## Visualization

The project includes various visualizations to present the analysis results:
- Bar charts for monthly sales and city sales.
- Line plots for order frequency by hour.
- Bar charts for product sales quantities.
- Dual-axis plots for product quantities and average prices.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
