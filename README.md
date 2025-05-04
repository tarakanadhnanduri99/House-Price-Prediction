🏠 House Price Prediction (Bengaluru)
This project predicts house prices in Bengaluru using machine learning techniques. A trained Ridge Regression model is deployed through a simple Flask web application, allowing users to input property details and receive real-time price predictions.

📁 Project Structure
bash
Copy
Edit
House-Price-Prediction/
├── templates/
│   └── index.html             # Frontend form for user input
├── Bengaluru_House_Data.csv   # Original dataset
├── Cleaned_data.csv           # Cleaned dataset used for modeling
├── Predictor.py               # Script for handling predictions
├── RidgeModel.pkl             # Trained Ridge Regression model
├── main.py                    # Flask app entry point
├── temp.py                    # Temporary or testing script
└── README.md                  # Project overview (this file)
🚀 Features
Clean and preprocess raw housing data

Train a regression model to predict prices

Deploy a web app using Flask to interact with the model

Real-time price prediction based on user input

🔧 Technologies Used
Python

Pandas, NumPy

Scikit-learn

Ridge Regression

Flask (for web deployment)

HTML (basic frontend)

⚙️ How to Run the Project
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/tarakanadhnanduri99/House-Price-Prediction.git
cd House-Price-Prediction
2. Install Dependencies
Make sure you have Python installed (preferably 3.7+), then install required packages:

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is not included, manually install:

bash
Copy
Edit
pip install pandas numpy scikit-learn flask
3. Run the Flask App
bash
Copy
Edit
python main.py
Go to http://127.0.0.1:5000/ in your browser to use the app.

🧠 Model
Algorithm: Ridge Regression

Serialized model: RidgeModel.pkl

Inputs: Square footage, number of bathrooms, bedrooms (BHK), location, etc.

Output: Predicted house price (in Lakhs)

🖥️ Web Interface
The UI built with index.html allows users to:

Enter square footage, BHK, and bath count

Choose the location from a dropdown

Submit form to get the predicted price

📬 Contact
Venkata Taraka Nadh Nanduri
Email: tarakanadh99@gmail.com
LinkedIn: linkedin.com/in/venkata-taraka-nadh-nanduri-39a069294
