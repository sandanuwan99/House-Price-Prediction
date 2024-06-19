# House Price Prediction

This project aims to predict house prices using a dataset of housing data. The dataset includes various features such as location, age of the house, number of rooms, and proximity to the ocean.

## Installation

To get started with the project, you need to install the dependencies. You can do this by running the following command:

pip install -r requirements.txt

Ensure you have the following packages installed:

numpy
pandas
matplotlib
Dataset
The dataset used in this project is housing.csv, which contains the following columns:

longitude
latitude
housing_median_age
total_rooms
total_bedrooms
population
households
median_income
median_house_value
ocean_proximity
You should have the housing.csv file in the same directory as the Jupyter notebook.

Project Structure
House Price Prediction.ipynb: The Jupyter notebook containing the code for data loading, exploration, preprocessing, and model training.
requirements.txt: List of Python dependencies required to run the project.
housing.csv: The dataset file.

Data Preprocessing
The data preprocessing steps include handling missing values, encoding categorical features, and scaling numerical features. Detailed preprocessing steps can be found in the House Price Prediction.ipynb notebook.

Model Training
The notebook contains the code for training a machine learning model to predict house prices. You can experiment with different algorithms such as Linear Regression, Decision Trees, and Random Forests.

Evaluation
After training the model, evaluate its performance using appropriate metrics such as Mean Squared Error (MSE) and R-squared score. The notebook includes code for evaluating the model's performance.

Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The dataset used in this project is based on the California Housing dataset.
Special thanks to the open-source community for providing valuable resources and tools.
