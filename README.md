# 📈 TCS Stock Price Prediction

This project builds **Machine Learning models** to predict **Tata Consultancy Services (TCS)** stock price movements and next-day closing prices using historical stock market data.

The models are built using **K-Nearest Neighbors (KNN)** for both **classification** (up/down movement) and **regression** (predict close price).

---

## 📂 Project Structure


---

## 💡 Features

- 📥 Download historical stock data using **yfinance**
- 🛠 Feature Engineering  
    - Open - Close
    - High - Low
- 🤖 Machine Learning Models  
    - **KNN Classifier** → Predicts Up/Down movement  
    - **KNN Regressor** → Predicts next day's Close price
- 🔍 **GridSearchCV** for hyperparameter tuning (find best `n_neighbors`)
- 📊 Performance evaluation:  
    - Classification Accuracy  
    - Regression RMSE (Root Mean Square Error)

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| **Python 3.12** | Programming language |
| **pandas** | Data manipulation |
| **numpy** | Numerical computation |
| **scikit-learn** | Machine Learning models |
| **yfinance** | Stock data download |
| **matplotlib** / **seaborn** | Data visualization |

---

## 📈 Example Output

| Actual Class | Predicted Class |
|--------------|-----------------|
| 1 | 1 |
| -1 | -1 |
| 1 | 1 |
| ... | ... |

**Train Accuracy**: 65%  
**Test Accuracy**: 48%  

---

## 🚀 How to Run

1️⃣ Clone repository  
```bash
git clone https://github.com/Al-Mahmud0/TCS-Stock-Prediction.git

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run Jupyter notebook
jupyter notebook TCS_Stock_Prediction.ipynb
