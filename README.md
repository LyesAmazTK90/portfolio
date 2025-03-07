# portfolio

Welcome to my GitHub portfolio! Here you will find a collection of five projects that I have worked on, covering various domains such as data visualization, machine learning, natural language processing, and business intelligence. Each project showcases my skills in different areas, ranging from building interactive applications to predictive modeling and clustering. Below is an overview of the projects:

Project 1: Interactive Application - Formula 1 Visualizations

This project is an interactive tool that visualizes various aspects of Formula 1 racing. Originally designed to explore driver performance, weather conditions, and race statistics, it has been extended to include environmental analytics, providing insights into carbon emissions, energy consumption, and sustainability practices in the racing world. The tool combines web scraping, data processing, and visualization techniques to deliver real-time insights that help analyze the environmental footprint of Formula 1 events.
Real-World Application: Environmental Analytics in Formula 1

Formula 1 has made commitments to sustainability, including a target to be net zero carbon by 2030. This tool can support F1 teams, sponsors, and environmental organizations by analyzing environmental impacts related to race events. By tracking data such as fuel consumption, CO₂ emissions from travel and logistics, and energy use at race venues, the app can help stakeholders make data-driven decisions to minimize environmental impact. Here are some examples of the insights it could provide:

    Carbon Emissions Tracking
    The tool can calculate and display estimated carbon emissions per race event based on factors like fuel consumption, number of flights, and logistics. This allows teams to identify high-emission locations and prioritize emissions reduction strategies.

    Energy Consumption Analysis
    Visualizations can show the energy usage associated with each race venue, including electricity and fuel usage for power generators. Comparisons between venues can highlight which circuits are more energy-efficient, and where renewable energy is being integrated effectively.

    Weather Impact on Sustainability
    By integrating weather data from OpenWeather, the app can assess how weather patterns influence energy usage (e.g., increased cooling demand during hot races) or affect emissions due to changes in fuel consumption and tire wear.

    Sustainability Performance Across Teams
    Using Airtable to store and track sustainability-related metrics, teams can monitor their progress toward net-zero goals. They can also compare their own metrics against other teams, creating an accountability framework for sustainable practices.

Key Modules and Environmental Analytics Enhancements

    scrape_f1.py: This module has been enhanced to pull additional data on race logistics and infrastructure energy use.
    airtable.py: An interface for managing and updating sustainability metrics for each race and team. This module tracks metrics like fuel consumption, CO₂ offsets, and renewable energy usage.
    graficos.py: Includes visualizations showing emissions trends, venue energy usage, and per-race sustainability scores. These visuals are designed to help teams, fans, and regulators understand the environmental impact of each race.
    ui.py: The user interface now includes additional dashboards focused on environmental analytics.

Modifications for Environmental Impact Analysis

To add your own environmental insights, you can:

    Update scrape_f1.py to collect race-specific environmental data, such as venue energy sources or local transportation emissions.
    Customize graficos.py to create visualizations of sustainability metrics, like a bar chart comparing emissions per race or a line chart showing emissions reductions over seasons.

Project Status

This project demonstrates the potential for Formula 1 racing to use data and analytics to reach ambitious sustainability goals.

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

This project leverages advanced machine learning techniques to provide actionable insights into customer segmentation, empowering the business to tailor its strategies effectively. Through clustering and dimensionality reduction, we aimed to classify clients in a way that directly supports targeted sales and marketing strategies, allowing for highly customized engagement based on the nuanced profiles of each segment.
Key Components:

    K-means Clustering: By applying K-means clustering, we identified distinct client segments based on purchasing patterns, sales volume, and market position. This technique uncovered core customer groups that differ in behaviors, needs, and potential for business growth, ranging from opportunistic buyers to high-value partners. Each cluster was designed to reflect real-world customer types, allowing the business to segment clients more intuitively.

    Principal Component Analysis (PCA): Using PCA, we reduced the dimensionality of the data, highlighting the most critical variables influencing customer behavior, such as net sales, product portfolio breadth, and purchase frequency. This dimensionality reduction enhanced interpretability and allowed for a more robust clustering model by removing noise from less impactful features.

Practical Applications in Real-World Scenarios:

    Sales Strategy Customization: By linking client segments with tailored sales strategies, the business can engage high-value clusters with partnership programs, while transactional clients may receive more standardized offerings. Each cluster's characteristics inform specific strategies, such as upsell opportunities for loyal buyers or high-touch engagement for rapidly growing accounts.

    Resource Allocation: With clearer customer profiles, sales and marketing resources can be optimized based on segment potential. For instance, high-growth or high-value segments may be prioritized for targeted campaigns, while smaller accounts can be efficiently managed through automated or scaled engagement strategies.

    Predictive Customer Classification: By training the model on existing clients, it can classify new or prospective clients, helping sales teams determine the likely segment and optimal strategy early in the customer journey. This approach gives the sales force a predictive advantage, enabling faster adaptation to client needs.

    By embedding analytics into operational workflows, the model generates real-time insights that enrich customer relationship management (CRM) systems. These insights can support performance tracking by segment, ROI analysis for marketing campaigns, and dynamic adjustments in strategy based on evolving client data.

Project Status

Completed - enables companies to personalize their sales approach based on detailed customer insights.

Project 5: XGBoost and Stacking Model for House Price Prediction

Overview
This project involved developing a robust predictive model using XGBoost, complemented by a stacked model ensemble approach, to accurately forecast house prices. The model was designed to predict housing sale prices based on an extensive feature set, capturing elements that directly influence property values.

Key Details
The project followed a meticulous data preprocessing pipeline, ensuring each feature was optimally prepared to enhance predictive accuracy:

    Data Cleaning and Preparation: Handled missing values for key numerical and categorical attributes, using strategies that consider real-world cases such as imputing mean values for continuous attributes (like lot size) and encoding property characteristics (e.g., year built, number of rooms).
    Feature Engineering: Selected impactful features based on domain relevance, which include structural, area, and aesthetic attributes, to mimic scenarios faced in real estate analytics.
    Modeling Strategy:
        Used XGBoost to harness its ability to capture complex patterns and interactions between housing attributes.
        Implemented a stacked ensemble model, combining XGBoost, Gradient Boosting, Lasso Regression, and Neural Network layers to optimize predictive capability across diverse property segments.

The model was evaluated using Root Mean Squared Error (RMSE) applied to the logarithmic transformation of sale prices, prioritizing accuracy across both high and low-end properties.

Real-World Relevance and Application
This approach is highly adaptable to scenarios in real estate market analysis, offering a valuable tool for understanding:

    Housing Market Dynamics: By predicting sale prices accurately, this model can provide insights into price trends, essential for advising clients on pricing strategies, investment opportunities, and neighborhood-level evaluations.
    Customized Market Assessments: Feature engineering and ensemble techniques allow for customization to specific local or client-defined parameters, enabling tailored analytics for different property types or regional market trends.
    Customer Segmentation and Sales Personalization: Through interpretability techniques, such as feature importance and Shapley values, the model can reveal key drivers in housing prices. This data can be translated into personalized recommendations for clients, offering actionable insights for real estate agencies or investors.

Project Status
Completed - Ready for deployment in market forecasting applications or as a foundation for further development of custom real estate insights solutions.


Project 6: E-Commerce Recommendation System

🔹 Overview

This project focuses on data analysis, session tracking, and personalized product recommendations using real-world e-commerce data. The dataset includes customer interactions, products, and session-based activity logs.

The project is structured into three main tasks:

    Task 1: Extract key insights from the dataset using queries.
    Task 2: Analyze session behavior (session duration & cart engagement).
    Task 3: Develop a personalized recommendation system using ALS (Alternating Least Squares).

🔹 Task 1: Data Analysis & Query Extraction
✅ Key Objectives

We extracted insights from the dataset using Pandas to understand user behavior, product interactions, and purchase patterns.
📌 Questions & Solutions

1️⃣ Find the smallest partnumber of a product with color_id=3 and a discount.

    Solution: Filtered products by color_id=3 and discount=1.
    Outcome: Found the product with the lowest partnumber.

2️⃣ Find the user with lowest F, highest R, and lowest user_id in the country with most users spending M < 500.

    Solution:
        Used an API to fetch user data (M, F, R, country).
        Cached the data to avoid re-fetching.
        Identified the country with the most users spending M < 500.
        Sorted users by F (ascending), R (descending), user_id (ascending).
    Final Answer: 187374

3️⃣ How many times is a product visited before being added to the cart (on average)?

    Solution: Computed visit_count / cart_count for each product.
    Outcome: Returned the average number of visits before adding to cart.

4️⃣ Find the most common device_type used for adding discounted products to the cart.

    Solution: Merged train data with products to find the most frequent device_type.
    Outcome: Identified the most common device type for discounted items.

5️⃣ Identify which top user (most interactions) uses device_type=3 the most.

    Solution:
        Found the top 3 users in each country.
        Checked who interacted with device_type=3 the most.
    Outcome: Identified the most active user on mobile devices.

6️⃣ Find the number of unique products interacted with outside a user’s registered country.

    Solution:
        Mapped user_id → country.
        Identified interactions where interaction_country ≠ registered_country.
    Outcome: Counted unique products interacted with across borders.

7️⃣ Find the most common pagetype for each product family in the first week of June.

    Solution:
        Merged train data with products.pkl to extract family.
        Grouped by family, pagetype to find the most frequent pagetype.
    Outcome: Identified which pages were most commonly viewed per product family.

🔹 Task 2: Session Analysis
✅ Objective

Analyze customer session behavior by calculating:

    Total session duration (seconds).
    Cart addition ratio (products added to cart / total products interacted with).

📌 Approach

    Step 1: Converted timestamps to datetime format.
    Step 2: Computed session duration as (last event - first event) per session.
    Step 3: Computed cart addition ratio as (items added to cart / total interactions).
    Step 4: Sorted results by user_id and session_id.

📌 Example Output

    user_id  session_id  total_session_time  cart_addition_ratio
0    3051.0       20301              47.208                0.000
1   51325.0        4465               0.000                0.000
2   62586.0       19184             520.169                0.125
3  185244.0       18588             121.659                0.000
4  271973.0        7503             109.557                0.000

    Short sessions with 0.000 cart ratio → Users who browsed but didn’t add items.
    Longer sessions with higher cart ratios → Engaged users likely to convert.

🎯 Real-world impact: Helps optimize session-based recommendations by understanding engagement levels.
🔹 Task 3: Personalized Product Recommendation System
✅ Objective

Develop a recommendation model to suggest five products per session.
📌 Approach

1️⃣ Data Preparation

    Loaded train, test, and product data.
    Mapped user_id and partnumber to ALS-compatible indices.

2️⃣ Train ALS Model (Collaborative Filtering)

    Built a user-item interaction matrix (sparse matrix).
    Trained Alternating Least Squares (ALS) to predict latent factors.
    Used 50 factors & 20 iterations for optimization.
    Output: User-item interaction matrix & ALS model.

3️⃣ Generating Recommendations

    For each session in test data:
        Checked if user exists in train data.
        Used ALS model to recommend 5 products per session.
        New users received empty recommendations (can be improved using hybrid models).

4️⃣ Saving Predictions

    Stored recommendations in predictions_3.json.
    Fixed JSON serialization issue (converted NumPy int64 → Python int).

📌 Example Output (JSON)

{
    "746": [],
    "1306": [],
    "1364": [],
    "4711": [27593, 15206, 38308, 33047, 23014],
    "15073": [948, 15206, 23014, 688, 20375]
}

    Empty lists ([]) → Sessions with no past interactions (new users).
    List of product IDs → Top 5 recommended products per session.

🔹 Real-World Applications

This project mirrors real-world recommendation engines used in:
🛍️ E-commerce (Zara, Amazon, ASOS)

✅ Personalized Product Recommendations → Improve conversion rates by suggesting relevant products.

✅ Session-Based Insights → Helps optimize shopping experience for mobile vs. desktop users.

✅ Cross-Border Shopping Analysis → Detects global shopping trends and localized demand.

🎬 Streaming (Netflix, Spotify, YouTube)

✅ User-Based Content Recommendations → Suggest movies, shows, music, or videos based on session activity.

✅ Hybrid Models (ALS + Content-Based Filtering) → Combine behavioral + content similarity.

🏪 Retail Analytics (Walmart, Target, Carrefour)

✅ Session Duration & Cart Analysis → Optimize store layouts (virtual or physical).

✅ Customer Segmentation → Identify new vs. returning customers for targeted marketing.

✅ Product Trends & Discount Optimization → Understand which discounts drive more engagement.


🎯 Key Takeaways

✅ Task 1: Extracted valuable user & product insights.

✅ Task 2: Analyzed session behavior & engagement.

✅ Task 3: Developed a scalable recommendation system.

🎯 Next Steps: 🚀 Improve recommendations for new users (cold-start problem).
🚀 Deploy API for real-time recommendations.
🚀 Test hybrid deep learning models (Transformers, Neural CF, LLMs).

🔥 This project can be applied to any recommendation-based industry! 🚀

Feel free to reach out for any questions about the project’s structure, methodology, or potential applications. I’m eager to discuss how these methods can be customized further to support specific business needs.
