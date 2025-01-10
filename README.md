# Crop_Yield_Predictor
This is a web application designed to predict crop yields based on various features such as year, average rainfall, pesticide usage, temperature, country, and crop type. 
# Crop Yield Prediction System

## Description
The Crop Yield Prediction System is a machine learning-powered web application that predicts agricultural crop yields based on various features such as year, average rainfall, pesticide usage, temperature, country, and crop type. Built using Flask for the backend and Bootstrap for the frontend, this system provides an easy-to-use interface for farmers, researchers, and agricultural agencies to estimate crop yields and make informed decisions.

## Features
- **Machine Learning Model**: Predicts crop yield using Decision Tree Regression based on user input.
- **Interactive Form**: Users can select the country and crop type from dropdown menus and input numerical data for rainfall, pesticide usage, temperature, and year.
- **Prediction Display**: Displays the predicted crop yield on the same page after form submission.
- **Responsive Design**: Mobile-friendly UI built using Bootstrap.
  
## Tech Stack
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Flask
- **Machine Learning**: scikit-learn (Decision Tree Regression)
- **Other Libraries**: Pandas, Numpy, Joblib

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/crop-yield-prediction.git
    ```
2. Navigate to the project folder:
    ```bash
    cd crop-yield-prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python app.py
    ```
5. Open a web browser and go to:
    ```
    http://127.0.0.1:5000/
    ```

## How It Works
1. **Input**: The user provides the year, rainfall (mm/year), pesticide usage (tonnes), average temperature (°C), country, and crop type.
2. **Processing**: The input is processed by the pre-trained machine learning model, which uses Decision Tree Regression to make predictions.
3. **Output**: The predicted crop yield is displayed on the webpage.

## Project Structure


Here's the analysis and README file you can use for your GitHub repository:

Analysis:
The Crop Yield Prediction System is built to assist in predicting agricultural crop yields based on various factors. The application combines web development and machine learning, leveraging a Flask-based web interface to collect inputs from the user and a pre-trained machine learning model to generate predictions.

Key Analysis Points:
Features Impacting Crop Yield Prediction:

Year: Crop yields tend to vary year by year due to changes in climate, weather conditions, and farming practices.
Rainfall (mm/year): Adequate rainfall is crucial for crop growth. Excessive or insufficient rainfall can drastically affect yields.
Pesticide Usage (Tonnes): The use of pesticides affects crop health and yield. Proper use can improve yields, while overuse or incorrect use can harm the crop and reduce yield.
Average Temperature (°C): Temperature fluctuations influence plant growth. Different crops have specific temperature needs, and deviations from the ideal can affect the yield.
Country: The country choice links to different climatic, soil, and agricultural conditions, making it a critical feature in yield prediction.
Crop Type: Different crops have varied yield potentials depending on environmental factors, and therefore, crop type is a vital feature in this prediction model.
Model Approach: The project uses machine learning techniques, including Decision Tree Regression, which are appropriate for predicting continuous variables like crop yield. The model was trained on historical data to learn patterns between the features and crop yields, ensuring that the system provides relevant predictions based on user inputs.

User Experience:

The user interface is designed to be intuitive and easy to navigate. Dropdowns allow users to select countries and crops, and input fields enable them to provide numerical data.
After data entry, the user can submit the form, and the system will process the input and display the predicted crop yield on the same page, enhancing the experience with real-time feedback.
Scalability:

The system can be expanded by adding more crop types, countries, and input features to increase the model’s predictive power.
It can also be extended to include more advanced models or integrate real-time data sources (such as weather APIs) to enhance prediction accuracy.
Potential Use Cases:

Farmers and Agronomists: To estimate crop yields and make data-driven decisions about crop management, irrigation, and pesticide application.
Researchers: To study the relationship between various environmental and agricultural factors and crop yields.
Agricultural Agencies: To monitor and forecast crop yields in different regions for planning and resource allocation.
README File for GitHub
markdown
Copy code
# Crop Yield Prediction System

## Description
The Crop Yield Prediction System is a machine learning-powered web application that predicts agricultural crop yields based on various features such as year, average rainfall, pesticide usage, temperature, country, and crop type. Built using Flask for the backend and Bootstrap for the frontend, this system provides an easy-to-use interface for farmers, researchers, and agricultural agencies to estimate crop yields and make informed decisions.

## Features
- **Machine Learning Model**: Predicts crop yield using Decision Tree Regression based on user input.
- **Interactive Form**: Users can select the country and crop type from dropdown menus and input numerical data for rainfall, pesticide usage, temperature, and year.
- **Prediction Display**: Displays the predicted crop yield on the same page after form submission.
- **Responsive Design**: Mobile-friendly UI built using Bootstrap.
  
## Tech Stack
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Flask
- **Machine Learning**: scikit-learn (Decision Tree Regression)
- **Other Libraries**: Pandas, Numpy, Joblib

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/crop-yield-prediction.git
    ```
2. Navigate to the project folder:
    ```bash
    cd crop-yield-prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python app.py
    ```
5. Open a web browser and go to:
    ```
    http://127.0.0.1:5000/
    ```

## How It Works
1. **Input**: The user provides the year, rainfall (mm/year), pesticide usage (tonnes), average temperature (°C), country, and crop type.
2. **Processing**: The input is processed by the pre-trained machine learning model, which uses Decision Tree Regression to make predictions.
3. **Output**: The predicted crop yield is displayed on the webpage.

## Project Structure

crop-yield-prediction/
│ ├── app.py 
# Main Flask application file
├── templates/ # HTML files for the frontend
│ ├── index.html 
# Main page template 
│ ├── static/ 
# Contains static files like CSS and JS 
│ ├── model/ 
# Contains trained machine learning model 
│ ├── dtr.pkl 
# Pickled machine learning model 
│ ├── preprocessor.pkl 
# Pickled preprocessor 
│ ├── requirements.txt 
# List of Python dependencies 
└── README.md 
# Project summary and instructions


## Dependencies
- Flask
- scikit-learn
- Pandas
- Numpy
- Joblib
- Bootstrap

## Future Improvements
- **More Crop Types**: Add more crop types and geographical regions to enhance prediction accuracy.
- **Real-Time Data**: Integrate real-time weather APIs to dynamically adjust predictions based on current data.
- **Other Models**: Experiment with other machine learning models (e.g., Random Forest, XGBoost) for improved accuracy.
  
## Contributing
Feel free to fork the repository and submit pull requests with improvements, bug fixes, or additional features.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

For any issues or questions, please open an issue in the repository.
