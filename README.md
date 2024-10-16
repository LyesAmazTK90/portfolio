# portfolio

Welcome to my GitHub portfolio! Here you will find a collection of five projects that I have worked on, covering various domains such as data visualization, machine learning, natural language processing, and business intelligence. Each project showcases my skills in different areas, ranging from building interactive applications to predictive modeling and clustering. Below is an overview of the projects:
Project 1: Interactive Application - Formula 1 Visualizations

This project is an interactive tool that visualizes various aspects of Formula 1 racing. It combines web scraping, data processing, and visualization techniques to deliver real-time insights on races, weather conditions, and driver performance.
How to Use

    Clone the repository: git clone
    Install dependencies: pip install -r requirements.txt
    Add your configuration details and credentials to example_config.ini and rename it to config.ini (included in .gitignore for privacy).
    Run the application:
        Use test_app.ipynb to run all cells and explore the interactive visualizations.
        Use app.py via the terminal: python3 app.py or python3 -m app.

Credentials

The app requires access to Airtable (for data storage) and OpenWeather (for weather-related data). Set up your Airtable and weather API credentials using setup.ipynb.
Key Modules

    scrape_f1.py: Web scraping of Formula 1 data into DataFrames.
    airtable.py: Provides an interface for managing data with Airtable.
    graficos.py: Visualizations built from the data imported via Airtable.
    ui.py: Contains the user interface logic.

Modifications

You can add custom visualizations by creating new functions in graficos.py or modifying the base data structures via setup.ipynb and scrape_f1.py.
Project Status

Completed - minor patches may be added in the future.
Project 2: Predictive Maintenance Model for Rotational Machines

In this project, I developed a machine learning model to predict failures in rotational machines based on sensor data (vibration levels, temperature, etc.). The model helps anticipate maintenance needs and prevent machine breakdowns, thereby improving operational efficiency.
Key Details:

    The model uses supervised learning to predict failures.
    It analyzes key features such as vibration patterns, temperatures, and performance metrics to identify early signs of potential failure.
    The goal is to apply the right maintenance at the right time to reduce downtime and costs.

Project Status

Completed - can be adapted for various types of industrial machinery.
Project 3: Sentiment Analysis App with Streamlit

This project involved building a sentiment analysis app that combines natural language processing (NLP) and voice sentiment analysis using Streamlit. The app processes text and voice inputs to determine user sentiment in real time.
Key Features:

    NLP-based text sentiment analysis using pre-trained models.
    Voice sentiment analysis using audio features.
    Real-time visualizations of sentiment scores.

Project Status

Completed - demonstrates the integration of multiple forms of input (text and voice) to provide sentiment insights.
Project 4: Client Segmentation and Clustering for Business Insights

This project focused on clustering and segmenting clients to better understand customer profiles and develop effective sales strategies. The goal was to classify new clients using unsupervised learning techniques like K-means and PCA (Principal Component Analysis).
Key Features:

    K-means clustering: Identifies distinct customer segments.
    PCA: Used to reduce dimensionality and identify the most important components.
    The model helps businesses apply customized strategies for each client group based on their behaviors and characteristics.

Project Status

Completed - enables companies to personalize their sales approach based on detailed customer insights.
Project 5: XGBoost Model for House Price Prediction

This project involved building a predictive model using XGBoost to forecast house prices. The model predicts the sale price of houses based on various features provided in the dataset.
Key Details:

    The model is evaluated using Root Mean Squared Error (RMSE) between the logarithms of predicted values and actual sale prices.
    The objective is to minimize prediction errors for both expensive and inexpensive houses equally.

Project Status

Completed - useful for understanding housing market trends and forecasting prices.

Feel free to explore each of these projects, and don't hesitate to reach out if you have any questions!
