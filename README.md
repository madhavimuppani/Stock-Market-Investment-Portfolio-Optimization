# Stock-Market-Investment-Portfolio-Optimization
Python, Jupyter Notebook
# Stock Portfolio Selection, Optimization, and Comparison

## Project Overview

This project focuses on stock portfolio selection, optimization, and benchmarking using data-driven strategies and quantitative tools. The goal is to analyze stocks across different sectors, identify the best performers using momentum trading strategies, optimize their allocation using Modern Portfolio Theory (MPT), and benchmark the performance of the optimized portfolio against the S&P 500 index. This comprehensive approach provides insights into stock portfolio optimization and evaluation.

---

## Project Workflow

### 1. **Stock Selection**
   - Selected 30 stocks from Jan 1, 2017, to Dec 31, 2021:
     - **10 stocks** each from the **Consumer Staples,' 'Healthcare,' and 'Communication Services**
   - These sectors were assigned by my mentor for analysis.

### 2. **Momentum Trading Strategy**
   - Implemented momentum trading on the 30 stocks:
     - **Condition**: Stay invested if the **8-day moving average (MA)** of a stock is higher than its **21-day MA**.
   - Identified the **top 3 performing stocks** for each sector based on this strategy (total of 9 stocks).

### 3. **Portfolio Optimization**
   - Optimized the portfolio of the 9 selected stocks using **Pyomo** and **IPOPT**:
     - Objective: **Maximize returns** for different levels of risk.
   - Selected an appropriate risk level to form the final **MPT Portfolio**.

### 4. **Benchmarking and Comparison**
   - Benchmarked the portfolio performance against the **S&P 500 index** for December 2, 2021, to December 31, 2022:
     - Applied both **Buy-and-Hold Strategy** and **Momentum Trading Strategy** to the S&P 500.
   - Compared the performance of the optimized MPT portfolio using:
     - Buy-and-Hold Strategy.
     - Momentum Trading Strategy.
   - Detailed analysis of results to evaluate performance under various strategies.

### 5. **Insights and Conclusions**
   - Provided conclusions and inferences based on the analysis.
   - Gained experience in stock portfolio selection, optimization, and performance evaluation.

---

## Repository Structure

- **BDM Project.ipynb**: Jupyter notebook containing the code, results, and documentation of the project.
- **README.md**: This file, providing an overview of the project for new users.

---

## Key Features

- **Momentum Trading Strategy**: Dynamic method to identify top-performing stocks based on moving averages.
- **Portfolio Optimization**: Leverages Modern Portfolio Theory to allocate weights for maximizing returns at varying risk levels.
- **Benchmarking**: Compares the optimized portfolio's performance against the S&P 500 using well-known strategies.
- **Comprehensive Analysis**: Combines quantitative techniques and visualizations for actionable insights.

---

## Tools and Technologies Used

- **Programming**: Python (with libraries such as Pyomo, Pandas, NumPy, Matplotlib, etc.)
- **Optimization**: Pyomo and IPOPT solvers.
- **Data Analysis**: Moving averages, return calculations, risk analysis.
- **Visualization**: Used plots to demonstrate performance comparisons and portfolio weights.

---


