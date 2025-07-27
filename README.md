# 🏘️ California Housing Price Predictor

This project uses a Deep Learning model (ANN) to predict housing prices based on various features of California housing data. A Gradio web interface is provided for easy interaction.

---

## 📌 Overview

- 🔢 **Model**: Artificial Neural Network (ANN)
- ⚙️ **Framework**: TensorFlow / Keras
- 🧪 **Scaler**: MinMaxScaler from Scikit-learn
- 🖼️ **Interface**: Gradio for real-time predictions
---

## 🗂️ Project Structure
├── model_ann.h5 # Trained ANN model
├── scaler.pkl # Saved MinMaxScaler
├── main.ipynb # Model training + Gradio interface
├── README.md # Project description
---

## 🧠 Model Input Features

| Feature               | Type    | Description                                      |
|------------------------|---------|--------------------------------------------------|
| `longitude`            | float   | Longitude of the location                        |
| `latitude`             | float   | Latitude of the location                         |
| `housing_median_age`  | int     | Median age of houses in the area                 |
| `total_rooms`         | int     | Total number of rooms                            |
| `total_bedrooms`      | int     | Total number of bedrooms                         |
| `population`          | int     | Population in the block                          |
| `households`          | int     | Number of households                             |
| `median_income`       | float   | Median income of the residents                   |
| `ocean_proximity`     | int     | Encoded category (0: <1H OCEAN, 1: INLAND, 2: NEAR OCEAN, 3: NEAR BAY, 4: ISLAND) |

---

## 🚀 How to Use

### 🛠️ Step 1: Clone the Repository
git clone https://github.com/ShivangGit123/housing-price-predictor.git
cd housing-price-predictor
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run the Application
python app.py
