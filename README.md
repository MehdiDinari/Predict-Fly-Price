# ✈️ Flight Price Prediction

## 📌 Overview
This project aims to predict flight ticket prices using machine learning techniques. The dataset includes various flight-related attributes such as airline, departure and arrival times, source and destination, and ticket price. The goal is to build a model that accurately predicts flight prices based on these factors.

## 🚀 Features
- ✅ Data preprocessing and cleaning
- 📊 Exploratory Data Analysis (EDA) with visualizations
- 🏗 Feature engineering and selection
- 🤖 Machine Learning model training and evaluation
- 🔍 Model performance comparison

## 🛠 Technologies Used
- 🐍 Python
- 📓 Jupyter Notebook
- 🏗 Pandas, NumPy (Data Manipulation)
- 🎨 Matplotlib, Seaborn (Data Visualization)
- 📈 Scikit-Learn (Machine Learning)

## 📥 Installation
### Prerequisites
Ensure you have Python installed. Then, install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Notebook
1. 🔽 Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. 📂 Navigate to the project folder:
   ```bash
   cd flight-price-prediction
   ```
3. 🏁 Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. 📜 Open `flight_price_prediction.ipynb` and run the cells.

## 📊 Dataset
The dataset consists of the following columns:
- ✈️ **Airline**: Name of the airline
- 📅 **Date_of_Journey**: Date of the flight
- 🌍 **Source**: Departure city
- 📍 **Destination**: Arrival city
- ⏰ **Dep_Time**: Flight departure time
- 🕒 **Arrival_Time**: Flight arrival time
- ⏳ **Duration**: Total flight duration
- 🛑 **Total_Stops**: Number of stops between source and destination
- 💰 **Price**: Ticket price (Target variable)

## 🏗 Model Building
1. 🔍 Data Preprocessing
   - Handle missing values
   - Convert categorical data to numerical format
   - Feature scaling
2. 🤖 Model Training
   - Train multiple regression models (Linear Regression, Random Forest, XGBoost, etc.)
   - Evaluate performance using metrics like RMSE, R2-score
3. ⚙️ Hyperparameter Tuning
   - Optimize model parameters for better accuracy

## 🎯 Results
The best-performing model is selected based on evaluation metrics and used to predict flight prices.

## 🔮 Future Enhancements
- 📆 Incorporate additional features such as weather conditions and holidays
- 🌐 Deploy the model using Flask or FastAPI
- 📡 Integrate with a real-time flight price API for live predictions

## 🤝 Contributions
Feel free to fork this repository and submit pull requests to improve the project!

## 📜 License
This project is licensed under the MIT License.
