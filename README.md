# Stock-Price-Forecasting-LSTM-GRU-BiLSTM
A deep learning project that forecasts stock closing prices using LSTM, BiLSTM, and GRU models. Includes feature engineering with technical indicators (MA20, MA50, RSI, MACD), experiments with different look-back windows, evaluation metrics (MAE, RMSE, R²), and next-day closing price predictions.
Project Description
Predict stock closing prices using deep learning models.
Uses multiple look-back windows to capture both short-term trends and long-term patterns.
Integrates technical indicators (MA20, MA50, RSI, MACD) for enhanced feature engineering.
Provides evaluation metrics like MAE, RMSE, and R² to measure prediction accuracy.
Produces next-day closing price forecasts.
This description helps anyone visiting the repo understand the problem, methods, and outputs immediately.

Features
Compare three models: LSTM, BiLSTM, and GRU.
Support for multiple look-back windows: 60 days, 360 days, and full history.
Includes feature engineering with moving averages, RSI, MACD.
Generates plots of actual vs predicted prices.
Produces a performance summary table with metrics and next-day predictions.
This section tells users what they get out of your project.


Installation
Clone the repository:

git clone https://github.com/yourusername/Stock-Price-Forecasting-LSTM-GRU-BiLSTM.git
cd Stock-Price-Forecasting-LSTM-GRU-BiLSTM

Install dependencies:
pip install -r requirements.txt
Simple steps make it easy for others to run your code immediately.

Usage

Run the main script:
python scripts/full_pipeline.py
Input a stock ticker symbol (e.g., MSFT).
The script will:
Download historical stock data using yfinance.
Train LSTM, BiLSTM, and GRU models with the specified look-back windows.
Plot train/test vs predicted prices.
Output a final performance summary table including the predicted next-day closing price.
This section guides users step by step so they can reproduce your results.
Sample Output Table
Provides a visual summary of all model performances and predictions.
Shows metrics like MAE, RMSE, R², and predicted next-day price.
Helps quickly identify the best-performing model.
Tables like this are very portfolio-friendly, showing your results in a clear, concise way.
Future Work / Extensions
Multi-step forecasting (predict next 5–10 days).
Ensemble models combining LSTM, BiLSTM, GRU for improved accuracy.
Transformers or attention-based models for sequence prediction.
Web-based UI/dashboard for real-time stock prediction.
Backtesting strategies to evaluate model performance for trading.
This section signals that your project has room to grow, which is great for research/portfolio purposes.

License

MIT License (see LICENSE file).
Free to use, modify, distribute, and sublicense with credit to you.
Protects you from liability and makes the project open-source friendly.

Repository Structure

Stock-Price-Forecasting-LSTM-GRU-BiLSTM/
├── data/                 Optional folder for sample CSVs or yfinance instructions
├── notebooks/            Jupyter notebooks for experiments, analysis, and visualization
├── scripts/              Python scripts including the main pipeline (full_pipeline.py)
├── outputs/              Folder to save plots, tables, and trained model files
├── LICENSE               MIT license file
├── README.md             This detailed project description
└── requirements.txt      Python dependencies needed to run the project
