# 🌦️ Delhi Climate Prediction using LSTM

This project demonstrates how Long Short-Term Memory (LSTM) networks can be effectively used for **time series forecasting**, particularly in predicting climatic conditions in Delhi. Implemented in Python using TensorFlow, this notebook provides a step-by-step guide from data preprocessing to model training and evaluation.

---

## 📌 Table of Contents

- [About the Dataset](#about-the-dataset)
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [License](#license)
- [Author](#author)

---

## 📊 About the Dataset

The dataset includes weather data collected in the city of Delhi over a 4-year period (2013–2016).  
It contains the following features:

- Date
- Mean Temperature
- Humidity
- Wind Speed
- Mean Pressure

Dataset Source: Provided within the notebook (`DailyDelhiClimateTrain.csv`).

---

## 📘 Project Overview

- This notebook applies **LSTM**, a type of recurrent neural network (RNN), to forecast future weather trends.
- Focused on **time series analysis** using a single feature from the dataset.
- Includes data preprocessing, sequence generation, model building, and training.

---

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib

---

## ▶️ How to Run

1. Open the notebook in Google Colab:
   👉 [Open in Colab](https://colab.research.google.com/drive/1YL14fnyfoThslOBkSFIXAhNaI44zY1yF)

2. Make sure the dataset (`DailyDelhiClimateTrain.csv`) is available in your Colab environment.

3. Run all cells to:
   - Load and visualize the data
   - Prepare the sequences
   - Train the LSTM model
   - Visualize predictions

---

## 📈 Results

- The LSTM model was able to learn patterns in temperature change over time.
- Visual plots compare true vs. predicted temperature values.

---

## 🪪 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Shahad Alhamili**  
AI Student & Engineer  
GitHub: [@Shahad-Alhamili](https://github.com/Shahad-Alhamili)
