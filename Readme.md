# Portfolio Optimization with Markowitz Model
---
```
Made by Milovan Marrder
```
## Project Overview

This project implements a portfolio optimization tool using the Markowitz Model. It allows investors to find the optimal asset allocation for a given set of investments, balancing risk and return based on their risk tolerance.

## Features

- Data input for multiple assets' historical returns
- Calculation of expected returns and covariance matrix
- Generation of random portfolios
- Visualization of the efficient frontier
- Identification of the optimal portfolio based on the Sharpe ratio
- Interactive plot for exploring different portfolio compositions

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- plotly

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/portfolio-optimization.git
   ```
2. Navigate to the project directory:
   ```
   cd portfolio-optimization
   ```
3. Install the required packages:
   ```
   pip install pandas numpy matplotlib plotly
   ```

## Usage

1. Open the Jupyter notebook or Python script in your preferred environment (e.g., Jupyter Lab, Google Colab).

2. Update the `Inversiones` list with your own asset data, or modify the code to read from a CSV file.

3. Set your total investment amount and maximum accepted risk:
   ```python
   total_inversion = 1430000  # Modify this to your investment amount
   max_accepted_risk = 0.20   # Adjust this value according to your risk tolerance
   ```

4. Run the cells/script to generate the portfolio analysis.

5. Explore the interactive plot to view different portfolio compositions and their respective risk-return profiles.

## Key Components

- `portfolio_performance()`: Calculates the return and risk of a given portfolio.
- Efficient Frontier Plot: Visualizes the risk-return tradeoff for different portfolio compositions.
- Optimal Portfolio Identification: Finds the portfolio with the highest Sharpe ratio within the accepted risk level.
- Interactive Plot: Allows users to explore different portfolio compositions by hovering over points in the scatter plot.

## Sample Output

The script provides several outputs:

1. A scatter plot showing the efficient frontier
2. Details of the optimal portfolio (maximum Sharpe ratio)
3. Asset allocation for the optimal portfolio
4. Pie chart visualizing the optimal portfolio's composition
5. Historical returns analysis based on the optimal allocation
6. Projected growth of the investment over 5 years

## Customization

You can customize the project by:
- Modifying the list of assets and their historical returns
- Adjusting the risk tolerance level
- Changing the total investment amount
- Adding new assets or removing existing ones from the portfolio

## Contributing

Contributions to improve the project are welcome. Please feel free to submit a Pull Request.

## Disclaimer

This tool is for educational purposes only. It does not constitute financial advice. Always consult with a qualified financial advisor before making investment decisions.
