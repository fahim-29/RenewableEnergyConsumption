This project focuses on analyzing renewable and non-renewable energy consumption data. The goal is to clean, visualize, and model energy trends to gain insights into how energy consumption is evolving over time
Data & Methodology
The dataset includes multiple energy sources recorded over several years across different regions. To make sense of the data, I followed these steps:

Data Cleaning & Preprocessing – Removing inconsistencies and handling missing values.
Exploratory Data Analysis (EDA) – Visualizing trends and patterns in energy consumption.
Predictive Modeling – Using machine learning techniques to forecast energy trends.
Machine Learning Models Used
For forecasting, I implemented two models:

Simple RNN (Recurrent Neural Network): Used for long-term energy consumption forecasting by learning complex patterns.
ARIMA (AutoRegressive Integrated Moving Average): Applied for time-series analysis, effectively capturing short-term fluctuations.
Key Findings & Results
Renewable energy consumption has shown a steady increase over time.
The ARIMA model accurately captures seasonal variations in energy usage.
The RNN model provides more stable long-term forecasts, making it useful for policy planning and energy management.
Technology Stack
The project was built using Python with libraries like Pandas, NumPy, Matplotlib, Seaborn, and Plotly for data analysis and visualization. Machine learning models were implemented using TensorFlow/Keras for RNN and Statsmodels for ARIMA in a Jupyter Notebook environment.
This project highlights the growing role of renewable energy and how machine learning can help us make data-driven decisions for the future. By understanding trends and forecasting energy consumption, we can better plan for a sustainable world.
