# Linear Regression Health Costs Calculator

This project is a part of the **Machine Learning with Python** certification from **freeCodeCamp**. The goal of this challenge is to develop a regression model that can accurately predict healthcare costs based on several factors such as age, BMI, smoking habits, and region.

## 🚀 Project Overview
In this challenge, I built a neural network-based regression model using TensorFlow and Keras. The objective was to achieve a **Mean Absolute Error (MAE)** of less than **$3500**, ensuring the model generalizes well to unseen data.

### Key Implementation Details:
* **Data Preprocessing:** Converted categorical features (sex, smoker, region) into numerical format using mapping.
* **Data Splitting:** Partitioned the dataset into 80% training and 20% testing sets.
* **Model Architecture:** * Input Layer based on feature count.
    * Multiple Dense layers with `ReLU` activation.
    * Output Layer with a single neuron for continuous value prediction.
* **Optimization:** Utilized the `Adam` optimizer with a tuned learning rate.
* **Training:** Trained for 1000 epochs to ensure convergence and minimize MAE.

## 🛠️ Technologies Used
* **Python**
* **Pandas & NumPy** (Data Manipulation)
* **Matplotlib** (Data Visualization)
* **TensorFlow & Keras** (Deep Learning Framework)

## 📊 Results
The model successfully passed the challenge with a **Mean Absolute Error (MAE)** significantly below the $3500 threshold.

## 🔗 Project Link
You can explore the full code and implementation in my Google Colab notebook:
👉 [Google Colab Notebook](https://colab.research.google.com/drive/1szco8xx4fVXBIBrGSjcvW9CbWZoDfKAp?usp=sharing)

---
*Completed as part of the freeCodeCamp Machine Learning Curriculum.*
