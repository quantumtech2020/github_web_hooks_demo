## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is shows how to create a GitHub Webhook to notify any organisation changes
	
## Technologies
Project is created with:
* Python flask
* ngrok

	
## Setup
To run this project, install python and Flask on your local machine. 
Create a folder on your C Drive ex. ForGitHub
Create a file listening_to_github.py in this folder
Create a Flask application
The Flask Application will run in the local host
127.0.0.1:5000

ngrok needs to be used to open localhost to external sites

The route will be 127.0.0.1:5000/github
It will be a post coming from Github
The Api will be called api_gh_message

The request content type will be a json file
Dump the Json into a dictionary


run this by running the Flask File
