# Flight Price Prediction Web Application
This web application predicts the price of flights based on various input parameters such as departure date and time, arrival date and time, source, destination, airline, and number of stops.

## Requirements
Python 3.8
Flask
Pandas
scikit-learn
Pickle
## Installation
Clone the repository to your local machine:

bash
Copy code
git clone < https://github.com/Sunilabhi/flight_price_prediction >
Navigate to the project directory:

bash
Copy code
cd <project-directory>
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt


## Usage
Ensure you have Python 3.8 installed on your machine.

Run the Flask web application:

bash
Copy code
python app.py
Open a web browser and go to <http://127.0.0.1:5000>

Fill out the flight details in the form and submit to get the predicted flight price.

## Files
app.py: Contains the Flask application code.
flight_pred_rf.pkl: Pickled machine learning model for flight price prediction.
templates/index.html: HTML template for the web application.
static/css/styles.css: CSS styles for the HTML template.
Customization
You can customize the HTML template (templates/index.html) and CSS styles (static/css/styles.css) to change the appearance of the web application.
You can train your own machine learning model and replace flight_pred_rf.pkl with your model file. Ensure that the input parameters and output format remain consistent.
## License
This project is licensed under the MIT License.

