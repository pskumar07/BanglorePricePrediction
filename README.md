Download Nginx to run the program and cut paste in Program Files Folder
![image](https://github.com/user-attachments/assets/0d7dd856-4389-4c8b-901d-344bb0ed3809)
![image](https://github.com/user-attachments/assets/afc1961a-810c-48a2-811a-64c515426ec4)

🏡 Bangalore House Price Prediction
This project predicts house prices in Bangalore using machine learning techniques. The dataset includes various real estate factors such as location, square footage, number of bedrooms, and more.

📌 Features
✔️ Data Cleaning & Preprocessing
✔️ Exploratory Data Analysis (EDA)
✔️ Feature Engineering
✔️ Machine Learning Model Training
✔️ Price Prediction

📂 Dataset
The dataset is sourced from Kaggle and contains real estate data, including:

Location 🏙️
Total square feet 📏
Number of BHKs 🛏️
Number of bathrooms 🚿
Price (Target Variable) 💰
🛠️ Tech Stack
Python 🐍
Pandas, NumPy 📊 (Data Processing)
Matplotlib, Seaborn 📈 (Visualization)
Scikit-learn 🤖 (Machine Learning)
Flask (Optional for Deployment) 🌐
🚀 Installation & Usage
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/pskumar07/BanglorePricePrediction.git
cd BanglorePricePrediction
2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook

bash
Copy
Edit
jupyter notebook
4️⃣ (Optional) Run Flask App for Web Deployment

bash
Copy
Edit
python app.py
📊 Model Training
Data Cleaning: Removed outliers, handled missing values
Feature Engineering: Converted categorical data using One-Hot Encoding
Model Used: Linear Regression
Performance Metrics: R² Score, Mean Absolute Error
🌐 Web App Deployment (Optional)
A simple Flask-based web app is included for users to input data and get price predictions.

📝 Future Enhancements
✅ Improve model accuracy using advanced ML models (e.g., Random Forest, XGBoost)
✅ Deploy model using Streamlit for a better UI
✅ Integrate Google Maps API for real-time location-based insights

🏆 Results & Insights
📌 Key Finding: Location has a significant impact on prices. Some overpriced areas were detected.
📌 Accuracy: The model achieves X% R² score on test data.
