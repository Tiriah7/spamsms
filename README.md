Dense ML model trained using Swahili and English spam and ham messages for the purpose of spam SMS detection
Flask server to connect to the Trained model
Android app connected to the flask server
App sends a Text message as a HTTP post to the server, where the server prepocesses the message and uses the model to get a prediction (whether spam or ham) and 
then sends the prediction back to the Android app for display
