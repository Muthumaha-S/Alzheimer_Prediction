# Alzheimer_Prediction

This repository contains a **Machine Learning pipeline** and a **Flask web application prototype** for predicting **Alzheimer’s disease**.  
It includes two notebooks: one for model development and one for app logic.

## Repository Structure
Alzheimer_Prediction/
│── main.ipynb # Core ML pipeline (data processing, training, evaluation)
│── app_py.ipynb # Flask application prototype for predictions
│── README.md # Project documentation


---

##  Project Overview
Alzheimer’s disease is a progressive neurological disorder.  
This project demonstrates:  
1. **Model Development** – training and evaluating ML models for Alzheimer’s prediction.  
2. **Flask App Prototype** – building an interactive application for running predictions on uploaded images.  

---

## ⚙ Features
- Data preprocessing & cleaning  
- Exploratory Data Analysis (EDA)  
- ML model training & evaluation  
- Flask-based interactive app for predictions  
- Visualizations of results  

---

## 🛠 Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **TensorFlow / Keras**
- **OpenCV**
- **Flask**
- **Jupyter Notebook / Google Colab**

---

## 📊 Results
- Built ML models to predict Alzheimer’s disease categories.  
- Evaluated performance using accuracy, precision, recall, and F1-score.  
- Developed a **Flask web app prototype** (`app_py.ipynb`) to demonstrate practical use.  

---

## 🔧 How to Run

### ▶️ 1. Run `main.ipynb` (Model Development)
1. Open `main.ipynb` in **Google Colab** or Jupyter Notebook.  
2. Run all cells to:
   - Load and preprocess the dataset.  
   - Train ML models.  
   - Evaluate performance.  
3. Results and visualizations will be shown directly in the notebook.  

---

### ▶️ 2. Run `app_py.ipynb` (Flask App Prototype)

#### Option A: Run in **Google Colab** with ngrok
1. Install dependencies:
   ```bash
   !pip install flask flask-ngrok tensorflow opencv-python
2.Run all cells → A public ngrok URL will appear (e.g. http://xxxx.ngrok.io).

 3.Open that link in your browser → Upload an image → Get Alzheimer’s prediction.
#### Option B: Run Locally (Recommended for development)

Clone the repository:

git clone https://github.com/Muthumaha-S/Alzheimer_Prediction.git
cd Alzheimer_Prediction


Install dependencies:

pip install flask tensorflow opencv-python


Place your trained model file (alzheimer_prediction_model.h5) in the project folder.

Run the app:

Either directly run app_py.ipynb in Jupyter Notebook.

Or copy its content into app.py and run:

python app.py


Open in browser → http://127.0.0.1:5000/
.
