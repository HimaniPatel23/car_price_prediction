# Car Price Prediction
## Objective
> This is a end-to-end machine learning model from Data Gathering to Heroku Deployment. I have created this project with help of <a href=https://github.com/krishnaik06/Car-Price-Prediction> Krishna Naik's </a> Tutorial (I did some minor changes with code in order to learn differnt concepts). 

## Dataset
> Dataset is available on Kaggle via <a href=https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho>here</a>. It is a regression problem where based on few features we have to predict the price of car (which is up for resale). It contains records about car such as:
1. Car name
2. year
3. Selling Price
4. Km_driven
5. Fuel
6. Seller Type
7. Transmission
8. Owner

## Model Creation
1. Read Data
2. Exploratory Data Analysis (Automatic and Manual)
3. Feature Engineering
4. Feature Importance using an Ensamble Model
5. Create a Machine Learning Ensamble Model
6. Use RandomSearchCV to identify hyperparameters for our ML model
7. Visualize results between actual vs predicted values
8. Export the model in pickle format

## Create a Flask app
1. Install Flask app
2. Import the model from pickle file
3. Define Home method to redirect user to html page
4. Define Predict method to predict values provided by user
5. Create html file in templates folder

## Run the app
1. Run jupyter notebook
2. Use Command Prompt to navigate to appropriate directory
3. Activate the conda environment
4. run command "python app.py"
5. Open the url in any web browser

## Other steps
1. Create a Procfile and paste <i>"web: gunicorn app:app"</i>
2. To create requirements.txt open terminal and activate conda environment. Run this command pip freeze > requirements.txt

## Heroku Deployment
1. Create an account in Heroku
2. Click create new app on top-right side
3. Create app name 
4. Link Heroku with github repo
5. Choose the branch you want to deploy
6. Click the button at the botton after all the libraries are installed

## References
1. Youtube Link: https://www.youtube.com/watch?v=p_tpQSY1aTs
2. Krishna Naik: https://github.com/krishnaik06/Car-Price-Prediction

## Disclaimer:
I created most of my repositories by learning from different sources like articles, youtube video. I do not own the code, I just use it for educational purposes and personal growth. 
