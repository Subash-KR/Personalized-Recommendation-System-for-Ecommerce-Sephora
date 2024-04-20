# Personalized-Recommendation-System-for-Ecommerce-Sephora

Sephora Personalized Recommendation System 🌟
Welcome to the Sephora Personalized Recommendation System repository! 💄👠🛍️


## 📜 Table of Contents

🚀 Introduction

📊 Data

🧹 Preprocessing

🛠️ Feature Engineering

🌟 Similarity Analysis

🤝 User Clustering

📢 Sentiment Analysis

🎁 Recommendation Engine

🔍 Filtering

🖥️ User Interface

🚀 Deployment

📋 Usage

🤝 Contributing

📄 License

##  🚀 Introduction
The Sephora Personalized Recommendation System is an innovative project aimed at providing tailored product recommendations to Sephora customers. Leveraging the power of data science and machine learning, we've created a system that understands your preferences, considers product similarities, and groups users to offer a unique shopping experience. 🛒✨

## 📊 Data
Our system utilizes two main datasets:

Review Dataset: Contains customer reviews and ratings for Sephora products.
Product Dataset: Contains information about Sephora's product catalog. 📦📊

## 🧹 Preprocessing
We took great care in preparing our data for analysis. Our preprocessing steps include:

Merging and cleaning the datasets.
Target encoding and label encoding for categorical features.
Imputing missing values using a Decision Tree-based approach.
Converting encoded columns back to their original states. 🧹🔍

## 🛠️ Feature Engineering
To enhance the recommendation system's performance, we engineered features by:

Creating a product-product similarity matrix:
Comparing ingredients using CHEMBERT.
Analyzing product names using TF-IDF.
Evaluating highlights with BERT embeddings. 💡🔍

## 🌟 Similarity Analysis
We understand that product similarity is crucial for personalized recommendations. Our system computes similarity scores based on various product attributes, ensuring that you receive recommendations that align with your preferences. 🤝📊

## 🤝 User Clustering
Not all customers are the same, and we acknowledge that. We've grouped users into different clusters based on their attributes, allowing us to provide recommendations that are more aligned with their individual tastes. 🧑‍🤝‍🧑🔍

## 📢 Sentiment Analysis
We care about the quality of your shopping experience. To ensure that our recommendations are based on authentic feedback, we've performed sentiment analysis on review titles and text. 📝🙂

## 🎁 Recommendation Engine
Our recommendation engine combines all the data and analysis to provide you with the most relevant product recommendations. Whether you're a makeup enthusiast or skincare aficionado, our system has something special for you. 🎁✨

## 🔍 Filtering
We understand that you may have specific interests. Our system allows you to filter recommendations based on product categories, so you can find exactly what you're looking for. 🧐🔍

## 🖥️ User Interface
We've created a user-friendly interface using tkinter for desktop applications and Streamlit for web deployment, ensuring that you can easily access and enjoy our recommendations. 💻🌐

## 🚀 Deployment
Our system is deployed and ready to serve you. Whether you prefer the desktop or web experience, we've got you covered. 🚀🌐

## Repository Structure

📦 Datasets - Contains all datasets used in the project.

🖼️ Images - Contains all images used in the project, such as logos, visualizations, etc.

📔 Notebooks - Contains Jupyter notebook files used for data analysis, experimentation, and documentation.

📄 Pages - Contains pages and templates for the website or application.

🚀 App.py - The main page or entry point of the website or application.

📋 README.md - This file, providing an overview of the repository.

📋 requirements.txt - Lists the Python packages and dependencies required to run the project.

🌐 Website - Website - https://personalized-recommendation-sephora.onrender.com/

## 📦 Datasets
This folder stores all the datasets used in the project. Ensure that datasets are organized and named meaningfully for easy access and usage.

## 🖼️ Images
The 'Images' directory houses all image assets required for the project. This includes logos, charts, and any other visual content.

## 📔 Notebooks
This directory contains Jupyter notebook files used throughout the project's development. Notebooks serve as a collaborative and interactive environment for data analysis, modeling, and documentation.

## 📄 Pages
The 'Pages' folder contains pages and templates for the website or application. This is where you'll define the structure, layout, and content of your project's user interface.

## 🚀 App.py
The 'App.py' file serves as the main entry point of the website or application. It's where you'll define the application's behavior and user interactions.

## 📋 README.md
This file provides an overview of the repository's structure and a brief introduction to the project. It serves as a starting point for users and contributors.

## 📋 requirements.txt
The 'requirements.txt' file lists all the Python packages and dependencies required to run the project. Make sure to keep this file up to date with the necessary dependencies for easy project setup.

Getting Started
To get started with the project, follow these steps:

Clone the repository to your local machine:

git clone https://github.com/your-username/repository-name.git

## 📋 Usage
Clone the repository.
Install the required dependencies.
Run the application for personalized Sephora recommendations. 🚀👩‍💻

## 🤝 Contributing
We welcome contributions from the community. Whether it's improving the recommendation algorithm, adding new features, or enhancing the user interface, your input is valued. 🤗🤝

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details. 📜📄

Thank you for choosing Sephora's Personalized Recommendation System. We're excited to provide you with a personalized shopping experience that will keep you coming back for more. Happy shopping! 🛒💄🎉

