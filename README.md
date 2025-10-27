# ml-stock-forecast-and-sentiment-webapp
# ML Stock Forecast and Sentiment Web App

A **Stock Market Forecasting Web Application** built with **Machine Learning** and **Sentiment Analysis** to predict short-term price movements for NASDAQ and NSE equities.  
The system integrates predictive modeling (**ARIMA**, **LSTM**, **Linear Regression**) with **Twitter sentiment analysis** to deliver actionable forecasts and recommendations.

---

## 📖 Table of Contents
1. [System Overview](#system-overview)
2. [Key Features](#key-features)
3. [Built With](#built-with)
4. [Installation Guide](#installation-guide)
5. [Screenshots](#screenshots)
6. [Authors](#authors)
7. [Links](#links)

---

## 🧠 System Overview

This application predicts stock prices for the **next seven days** and integrates **real-time sentiment analysis of tweets** to determine whether the stock is expected to **rise or fall**.  
It features a **Flask + WordPress hybrid front-end**, a **Python-based backend**, and a lightweight **MySQL** database powered by XAMPP.


## 🌟 Key Features

**Users can:**
- Register and log in securely  
- View **real-time stock prices**
- Access **latest financial news**
- Use a **currency converter**
- Edit/delete their own profile
- Learn about stocks and download ticker lists
- Forecast **7-day prices** for NASDAQ & NSE stocks

**Admins can:**
- Manage user accounts (CRUD operations)
- Trigger **automated email alerts**
- Access all user-level functionalities

---

## 🖼️ Screenshots

<img src="https://github.com/kaushikjadhav01/Stock-Market-Prediction-Web-App-using-Machine-Learning-And-Sentiment-Analysis/blob/master/screenshots/banner.png">
<img src="https://github.com/kaushikjadhav01/Stock-Market-Prediction-Web-App-using-Machine-Learning-And-Sentiment-Analysis/blob/master/screenshots/banner2.PNG">
<img src="https://github.com/kaushikjadhav01/Stock-Market-Prediction-Web-App-using-Machine-Learning-And-Sentiment-Analysis/blob/master/screenshots/11-resuts.png" width="750">
<img src="https://github.com/kaushikjadhav01/Stock-Market-Prediction-Web-App-using-Machine-Learning-And-Sentiment-Analysis/blob/master/screenshots/wp-admin.PNG" width="750">

---

## 🧱 Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-red?style=for-the-badge&logo=keras&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-blue?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-green?style=for-the-badge&logo=pandas&logoColor=white)
![WordPress](https://img.shields.io/badge/Wordpress-006699?style=for-the-badge&logo=wordpress&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

---

## ⚙️ Installation Guide

1. **Install XAMPP**
2. Download WordPress setup 
3. Extract into your XAMPP `htdocs/` folder
4. Edit `wp-config.php` to include your MySQL credentials
5. In phpMyAdmin, create a database called `wordpress`
6. Import `wordpress.sql` into it
7. Clone this repository and install dependencies:
   ```bash
   pip install -r requirements.txt
   python main.py
Visit localhost/wordpress to access the web app

