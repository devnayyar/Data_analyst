# E-commerce Data Analysis Project

## Overview

This project showcases a comprehensive analysis of an e-commerce dataset using SQL and pandas in Python. The primary goal is to derive actionable insights that can help inform business decisions and strategies. The analyses cover various aspects of the dataset, including revenue growth, customer behavior, product performance, and retention rates.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Data Analysis](#data-analysis)
  - [Monthly Revenue Growth Analysis](#monthly-revenue-growth-analysis)
  - [Top Customers Identification](#top-customers-identification)
  - [Recent Revenue Calculation](#recent-revenue-calculation)
  - [Product Variant Analysis](#product-variant-analysis)
  - [High Quantity Orders](#high-quantity-orders)
  - [Monthly Average Order Amount](#monthly-average-order-amount)
  - [Advanced Analyses](#advanced-analyses)
- [Technical Skills Demonstrated](#technical-skills-demonstrated)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project is organized as follows:
```
ecommerce-data-analysis/
│
├──  ecommerce.db  # SQLite database file
├── task1.ipynb  # Jupyter Notebook containing the analysis
├── README.md  # Project README file
```

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/devnayyar/Data_analyst
    cd Data_analyst
    ```

2. **Set up a virtual environment and install dependencies**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Ensure you have the SQLite database file** (`ecommerce.db`) in the `data` directory.

## Data Analysis

### Monthly Revenue Growth Analysis
- Calculated monthly revenue for the past year.
- Determined month-over-month growth rates to identify trends and highlight significant changes in revenue.

### Top Customers Identification
- Identified the top 3 customers based on their total spending.
- Provided insights into customer purchasing behavior and loyalty.

### Recent Revenue Calculation
- Calculated the total revenue generated in the last 3 months.
- Assessed recent financial performance to inform business decisions.

### Product Variant Analysis
- Counted distinct product variants sold within each category.
- Highlighted categories with the highest product diversity and sales.

### High Quantity Orders
- Identified customers with orders exceeding a quantity of 15 items.
- Provided insights into bulk purchasing behavior and potential B2B customers.

### Monthly Average Order Amount
- Calculated the average order amount for each month in the current year.
- Highlighted months with the highest average order values.

### Advanced Analyses
1. **Monthly Revenue Growth**:
   - Analyzed revenue changes by comparing the current month's revenue with the previous month's revenue.

2. **Product Purchase Analysis**:
   - Investigated customer purchase behavior for a specific product.

3. **Customer Retention Rate Calculation**:
   - Calculated the retention rate of customers over the last 12 months.

4. **Unsold Products in the Last 6 Months**:
   - Identified products that have not been sold in the last 6 months.

5. **Category-Specific Customer Insights**:
   - Analyzed customers who exclusively purchase products from a specific category, such as Electronics.

## Technical Skills Demonstrated

- **SQL**: Crafted complex queries to extract and manipulate data efficiently.
- **Pandas**: Utilized pandas for data manipulation, cleaning, and analysis.
- **Analytical Thinking**: Applied logical and analytical skills to derive actionable insights from raw data.

## Results

The detailed results of the analyses are documented in the Jupyter Notebook (`notebooks/analysis.ipynb`). This notebook provides a step-by-step explanation of each analysis, along with the corresponding SQL queries and pandas operations.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

