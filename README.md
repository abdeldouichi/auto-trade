# C++ Program for Risk-Based Investment Portfolio Optimization

## 📌 Overview
This project is a **C-based investment optimization tool** that helps traders and investors make smarter decisions by balancing **risk** and **return** within a given budget.  
By defining a **maximum acceptable risk percentage** and **total investment budget**, the program analyzes available assets and calculates the optimal fund allocation to maximize returns without exceeding risk limits.

## ✨ Features
- 📊 **User Inputs**: Define your acceptable risk percentage and total investment budget.
- 📂 **Asset Data Handling**: Read and process asset details such as:
  - Expected return rate
  - Risk score (volatility)
  - Minimum investment amount
- 📈 **Risk–Return Analysis**: Evaluate each asset’s potential based on performance and risk.
- ⚙ **Portfolio Optimization**:
  - Ensure portfolio risk ≤ user-defined limit.
  - Stay within total investment budget.
  - Maximize expected returns.
- 📝 **Report Generation**: Output recommended fund allocations, expected return, and total risk.
- 💡 **Practical Use**: Ideal for simulated trading strategies, academic projects, or financial modeling demos.

## 🛠 Implementation Details
- **Language**: C
- **Data Input**: From user input or asset file (CSV/structured text)
- **Possible Algorithms**:
  - Greedy approach for simplicity
  - Dynamic programming for better accuracy
  - Markowitz Modern Portfolio Theory for realistic finance modeling

## 🚀 How It Works
1. **User inputs**:
   - Maximum risk percentage
   - Investment budget
2. **Program loads asset data** (either from a file or predefined list).
3. **Risk–return analysis** is performed for each asset.
4. **Optimization algorithm** allocates funds to maximize return within constraints.
5. **Results** are displayed on the console and optionally saved to a file.

## 📂 Example Output
Enter max risk percentage: 15
Enter total budget: 10000

## Optimized Portfolio:
Asset Allocation Risk% Expected Return
Stock A $3000 4.5% 8.2%
Bond B $2000 1.2% 3.1%
ETF C $5000 9.0% 6.8%

Total Risk: 14.7%
Expected Total Return: 7.2%


## 🎯 Goal
To provide an accessible, efficient, and customizable investment planning tool that applies portfolio optimization principles in a C programming environment.

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
