# mobile-phone-pricing-
https://colab.research.google.com/drive/1EXJCIfE5FJ0pMe6qFpjs3nsuMdBFmN1E?usp=sharing


📱 Mobile Phone Price Range Prediction using Random Forest

Mobile phones come with a wide range of features such as RAM, battery capacity, camera quality, processor speed, and connectivity options. These features greatly influence the price of a mobile phone. Predicting the price range manually based on specifications can be difficult.

This project uses **Machine Learning** to predict the **price range of mobile phones** (Low, Medium, High, Very High) based on their technical specifications. The **Random Forest Classifier** is used as the main algorithm due to its high accuracy and reliability.

 🎯 Problem Statement

To build a machine learning model that can accurately classify mobile phones into different price ranges using their hardware and software features.

 📊 Dataset

Dataset Name: `mobile_price.csv`
Type: Structured tabular data
Target Column: `price_range`

Price Range Labels

| Value | Category       |
| ----- | -------------- |
| 0     | Low Cost       |
| 1     | Medium Cost    |
| 2     | High Cost      |
| 3     | Very High Cost |

 🧾 Features Included

* Battery Power
* RAM
* Internal Memory
* Screen Resolution
* Camera Quality (Front & Rear)
* Processor Cores
* Clock Speed
* Mobile Weight
* Connectivity Features (WiFi, Bluetooth, 3G, 4G)
* Touch Screen, Dual SIM

 🤖 Algorithm Used

Random Forest Classifier

Random Forest is a supervised machine learning algorithm that builds multiple decision trees and combines their results to improve accuracy and reduce overfitting. It is well-suited for multi-class classification problems.

 🛠️ Tech Stack

Programming Language: Python
Libraries:

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn
Tools:

  * Google Colab
  * Jupyter Notebook
  * GitHub

 ⚙️ Project Workflow

1. Data Loading
2. Data Exploration and Visualization
3. Feature Selection
4. Train-Test Split
5. Feature Scaling
6. Model Training using Random Forest
7. Model Evaluation
8. Price Range Prediction

✅ Results

* Achieved **high accuracy (~95%)**
* Random Forest performed better compared to other models
* Identified important features influencing mobile price




