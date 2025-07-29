# ✈️ Flight Price Prediction using Machine Learning

This project predicts flight prices based on various features such as departure/arrival time, airline, source/destination cities, and duration using machine learning models.

## 📂 Project Structure

```
📁 flight-price-prediction/
├── flight_price_prediction.ipynb
├── flight_price_prediction.html
├── Data_Train.xlsx
├── Test_set.xlsx
├── rf_random.pkl
├── README.md
├── requirements.txt
```

## 🧠 Features Used
- Date of Journey
- Departure & Arrival Time
- Duration
- Total Stops
- Airline
- Source and Destination

## 📊 Model Used
- **Random Forest Regressor**
  - Tuned using `RandomizedSearchCV`
  - Stored in `rf_random.pkl`

## 🛠️ Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/flight-price-prediction.git
   cd flight-price-prediction
   ```

2. Open the notebook:
   ```bash
   jupyter notebook flight_price_prediction.ipynb
   ```

3. Train the model or load the trained model from `rf_random.pkl`.

## 📈 Model Performance

- Evaluation Metrics used:
  - R² Score
  - Mean Absolute Error
  - Mean Squared Error
  

---

## License

This project is licensed under the MIT License.
