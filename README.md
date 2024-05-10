![BHP_Website](https://github.com/Anshika32/Bangalore-House-Prices/assets/121334039/d3d17245-f72c-4eb9-8088-ae352b57dd4c)

# Bangalore-House-Prices

## Overview

This project aims to predict house prices in Bangalore, India, using machine learning techniques. The prediction model is deployed using a Flask server, and a client-side interface is provided for users to input parameters and get price predictions.

## Project Structure

The project is organized into three main folders:

**client:** This folder contains the client-side interface for the house price prediction application. It includes HTML, CSS, and JavaScript files to create a user-friendly web interface. Users can input parameters such as location, total square feet area, number of bedrooms (BHK), and number of bathrooms to get a price prediction.

**model:** The model folder contains the machine learning model and related files. It includes a Jupyter notebook file (*.ipynb) where the model was trained and evaluated, a pickle file (*.pickle) containing the trained model, and a JSON file (columns.json) containing information about the data columns used by the model.

**server:** This folder contains the Flask server application responsible for serving the machine learning model and handling client requests. It includes Python files (*.py) defining the server routes and logic. The server provides endpoints for getting location names and predicting house prices based on user input.

