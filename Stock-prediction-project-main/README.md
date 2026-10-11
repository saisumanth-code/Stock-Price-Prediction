# Real-World Data Project: Stock Price Prediction (Finance)

## 📌 Objective
Predict the next day's stock closing price using historical price and 
volume data, applying an end-to-end data science workflow in a 
real-world financial context.

## 📊 Dataset
`stock_prices.csv` — 500 trading days of historical OHLCV (Open, High, 
Low, Close, Volume) data.

## 🔍 Process

**1. Data Loading & Overview**
- Loaded historical stock price data and reviewed its structure

**2. Exploratory Analysis**
- Visualized the closing price trend over time
- Reviewed statistical summaries of price and volume

**3. Feature Engineering**
- Created 7-day and 30-day moving averages to smooth short-term noise
- Calculated daily return (percentage price change)
- Defined the prediction target as the next day's closing price

**4. Correlation Analysis**
- Built a correlation heatmap to identify which features most 
  influence future price movement

**5. Model Training**
- Split data chronologically (80% train / 20% test) to respect the 
  time-series nature of the data
- Trained a Linear Regression model
- Trained a Random Forest Regressor for comparison

**6. Model Evaluation**
- Evaluated both models using RMSE (Root Mean Squared Error) and R² Score
- Visualized actual vs predicted closing prices on the test set
- Identified the most influential features using feature importance

## 📈 Results

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | [fill in] | [fill in] |
| Random Forest | [fill in] | [fill in] |

## 💡 Key Insights
- [Fill in: e.g. "The 7-day moving average was the strongest predictor 
  of next-day closing price"]
- [Fill in: e.g. "Random Forest slightly outperformed Linear Regression, 
  suggesting non-linear patterns in price movement"]

## ⚠️ Limitations
- Stock price prediction is inherently difficult due to market 
  volatility and external factors (news, economic events) not captured 
  in historical price data alone
- Dataset is simulated for learning purposes and does not reflect real 
  market behavior
- Models built here are for educational purposes only and not suitable 
  for actual trading decisions

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🚀 How to Run
1. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
2. Open `stock_prediction.ipynb` in VS Code or Jupyter
3. Run all cells to reproduce the analysis and predictions

## 📌 Outcome
This project applied core data science skills — feature engineering, 
regression modeling, and model evaluation — to a real-world financial 
prediction problem, demonstrating how historical price patterns can be 
used to forecast short-term stock movement.

## 👤 Author
[Your Name] — Data Science Intern
