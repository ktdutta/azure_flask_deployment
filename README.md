# azure_flask_deployment

## My First Deployed Application URL 
https://keerthana-504-flask.azurewebsites.net/

# How to Set Up & Deploy an Application 

## Initiating a New Flask Application 

For the purposes of this assignment the flask application provided by the professor was copied and pasted into our Google Shell Environment. 

1. Create a new GitHub Repository for your project 
2. Copy the GitHub Respository URL inorder to work on the repo in the Google Shell Environment 
3. Open up a Google Shell Envionrment in a new tab
4. Paste the url within the code ***git clone url***
5. Go to file and open up your cloned reposiotry
6. Create a python file named ***app.py*** within the repository
7. Within this file copy the flaskapp0 code provided by the professor and paste it within this file
8. In order to set up Jingas templating for html create a new templates folder
9. Within this folder create a base.html file
10. Copy the code provided in the professor's base.html file into yours which will create a template for the formatting of your application
11. In order to make the application more original make changes to the title and pages in th website

## Deploying the Application 

1. You must first log into Microsoft Azure through Google Shell using an activation code which will be provided to you
2. then you can deploy the app utilizing the code ***az webapp up --name--runtime PYTHON:3.9 --sku B1***
