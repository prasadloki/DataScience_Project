# 📈 AAPL Stock Price Prediction using LSTM & Streamlit

This project uses an LSTM (Long Short-Term Memory) deep learning model to predict Apple Inc. (AAPL) stock prices based on historical data. It is deployed as an interactive Streamlit web application, allowing users to explore actual vs. predicted stock prices in a simple and intuitive UI.

---

## 🚀 Features

- Fetches and visualizes historical AAPL stock data
- Preprocesses data for time series forecasting
- Builds and trains an LSTM model using Keras
- Plots actual vs. predicted prices
- Fully deployable with [Streamlit](https://streamlit.io)

---

## 🧠 Technologies Used

- Python 3.10+
- Streamlit
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- Keras & TensorFlow
- yfinance

---

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prasadloki/DataScience_Project.git
   cd DataScience_Project
   ```

2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

   Or manually install the essentials:
   ```bash
   pip install streamlit yfinance pandas numpy matplotlib scikit-learn tensorflow
   ```

3. **Run the Streamlit app:**
   ```bash
   streamlit run AAPL_streamlit_deploy.ipynb
   ```

---

## 📊 Sample Output

- 📉 Line plot comparing real and predicted prices
- 📅 Forecasting graph for the next period
- ℹ️ Informative layout with headers, markdowns, and styling

---

## 🗂️ File Structure

```
├── AAPL_streamlit_deploy.ipynb    # Main notebook with Streamlit integration
├── README.md                      # This file
```

---

## ✅ TODO

- Add model saving/loading to skip retraining
- Integrate user input for custom stock selection
- Include performance metrics (e.g., RMSE, MAE)

---

## 📬 Contact

If you have any feedback or questions, feel free to reach out at [bodduboinaprasad@gmail.com](mailto:bodduboinaprasad@gmail.com) or raise an issue on [GitHub](https://github.com/prasadloki/DataScience_Project).
