# Deployment to Heroku

This code deploys the Resnet50 model trained on IRiS data to detect the image class. 
Flask is used to build the web application and the trained resnet50 model is used to predict the classes of the image.

app.py calls the base HTML template which gets the image for which class ahs to be predicted and returns the predicted class on the webpage
