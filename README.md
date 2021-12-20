# Linux-Server-Flask-App
In this mini project I deployed a basic python flask application on a Linux server. The Linux server is on a  virtual machine in Microsoft Azure and is running [NGINX](https://www.nginx.com/resources/wiki/start/topics/tutorials/install/) to forward the request from the public IP address of the server to the local webserver. Gunicorn is also used to run our flask application.

Link to the App: http://20.122.197.198/ (VM Currently Turned Off)

## Application Breakdown

The construction of the application broken down into the parts below:

- [Python](https://www.python.org/) 
- [Flask (Python Framework)](https://flask.palletsprojects.com/en/1.1.x/)



### Deployment Platform

- Linux Server hosted in Microsoft Azure
