# 🌾 Crop Recommendation System 🌾

This project aims to recommend the most suitable crop for cultivation based on specific soil and weather conditions using machine learning algorithms.

## 🌟 Project Overview

The project includes the following steps:

1. **📂 Data Loading and Preprocessing**: The crop recommendation dataset is loaded from a CSV file and preprocessed, including normalization and standardization of features.
2. **🔍 Exploratory Data Analysis (EDA)**: Exploratory data analysis is performed to understand the distribution of data, check for correlations, and gain insights into the features.
3. **🛠️ Model Building**: Several machine learning algorithms are trained on the preprocessed data to predict the best crop for given conditions.
4. **📊 Model Evaluation**: The trained models are evaluated using accuracy metrics.
5. **🚀 Model Deployment**: The best-performing model is deployed in a web application to provide crop recommendations based on user input.

## 📊 Dataset

The dataset used for this project contains the following features:

- 🌿 Nitrogen (N)
- 🌱 Phosphorus (P)
- 🌻 Potassium (K)
- 🌡️ Temperature (°C)
- 💧 Humidity (%)
- 🌍 pH
- 🌧️ Rainfall (mm)

The target variable is "label," indicating the recommended crop.

## 🤖 Models Used

- **Logistic Regression**
- **Gaussian Naive Bayes**
- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Extra Tree**
- **Random Forest**
- **Bagging Classifier**
- **Gradient Boosting Classifier**
- **AdaBoost Classifier**

The Random Forest Classifier performed the best with an accuracy of approximately 99.32%.

## 🛠️ Usage

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/crop-recommendation-system.git
cd crop-recommendation-system
```

### 2. Install dependencies:

```bash
pip install -r requirements.txt
```

### 3. Run the web application:

```bash
python app.py
```

### 4. Access the application:

Open your web browser and navigate to `http://127.0.0.1:5000/` to access the crop recommendation system.

## 🌐 Web Application

The web application allows users to input soil and weather conditions to get a crop recommendation. The form accepts the following inputs:

- 🌿 Nitrogen (N)
- 🌱 Phosphorus (P)
- 🌻 Potassium (K)
- 🌡️ Temperature (°C)
- 💧 Humidity (%)
- 🌍 pH
- 🌧️ Rainfall (mm)

After submitting the form, the application will display the recommended crop.

## 💾 Model Training and Saving

The model training code processes the data and trains various models. The best model is saved using pickle for later use in the web application.

## ✅ Conclusion

This project successfully builds a machine learning model to recommend the most suitable crop for cultivation based on soil and weather conditions. The model is integrated into a web application that allows users to input their data and receive crop recommendations.
