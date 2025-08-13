# GMF Investments: Time Series Forecasting & Portfolio Optimization

## 📖 Project Summary

This project is a **comprehensive financial analysis workflow** built for **Guide Me in Finance (GMF) Investments**.  
Its purpose is to improve personalized portfolio strategies by applying **time series forecasting** and **Modern Portfolio Theory (MPT)** for data-driven decision-making.

The overarching objectives are to:

- 📈 Anticipate market movements  
- ⚖️ Determine the most efficient asset allocation  
- 🔁 Validate strategies through backtesting

---

We have completed **Task 1: Data Exploration & Preprocessing**, which involved:

- ⚙️ Creating a **reliable, reproducible data pipeline**
- 🧹 Cleaning raw market data for **TSLA**, **BND**, and **SPY**
- 📊 Performing **exploratory data analysis** to evaluate **risk** and **return** characteristics

## 📂 Project Structure

The repository is organized into clear, modular folders:

### 📓 notebooks/
Interactive Jupyter notebooks for analysis and development:

- **EDA.ipynb**: Contains data loading, cleaning, and exploratory analysis (Task 1).  
- **Forecasting.ipynb**: Will hold the code for Task 2 (time series modeling).  
- **Portfolio_Optimization.ipynb**: Will implement Tasks 3–5 (forecasting, portfolio optimization, and backtesting).

### 🧠 src/
Reusable Python modules for a clean, maintainable codebase:

- **data_loader.py** — Data fetching and preprocessing  
- **eda.py** — Visualization and statistical analysis functions  
- **models.py** — Forecasting model building and evaluation (future)  
- **portfolio.py** — Portfolio optimization functions (future)  
- **backtest.py** — Strategy backtesting functions (future)

### 📁 data/
Project datasets:

- **raw/** — Original YFinance data  
- **processed/** — Cleaned, modeling-ready data

### 🖼️ images/
All generated charts and plots.

### 📄 requirements.txt  
List of all Python dependencies.

---

## 🛠️ Setup & Execution

### 1. Environment Setup

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Samrizee/GMF-portfolio-forecasting.git
   cd GMF-portfolio-forecasting
