# Cars24_Price_Prediction
A Streamlit web app that predicts used car prices based on features like fuel type, engine power, transmission, and seats using a multiple linear regression model trained on Cars24 data. Built with Python, pandas, scikit-learn, and deployed for real-time predictions.

This project is a machine learning-based web application developed to predict the selling price of used cars. The model is trained on a dataset inspired by Cars24, a well-known platform for buying and selling second-hand vehicles in India. The application leverages a Multiple Linear Regression model built using scikit-learn, and it takes into account several key car attributes including the year of purchase, fuel type, transmission type, kilometers driven, engine capacity, mileage, maximum power, number of seats, and seller type.

The model is integrated into an interactive Streamlit web interface, allowing users to input specific car details and receive a real-time price prediction. The application is designed to simulate how predictive analytics can support informed decision-making in the automobile resale market. To ensure ease of use and maintainability, the model is saved using Python’s pickle module and loaded during runtime for prediction.

The project also includes essential data preprocessing steps, such as label encoding of categorical variables and handling of missing values.
This tool showcases the practical application of data science in the automotive domain and serves as a foundational project for those interested in combining machine learning with interactive web development.
