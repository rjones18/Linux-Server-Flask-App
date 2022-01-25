# Linux-Server-Flask-App
In this mini project I deployed a python flask application on a Linux server. The application is a food website in which you can upload pictures of your favorite food and it will post to the web page. The pictures are being stored in a azure storage account and can be deleted from the webpage from there. The Linux server is on a virtual machine in Microsoft Azure and is running [NGINX](https://www.nginx.com/resources/wiki/start/topics/tutorials/install/) to forward the request from the public IP address of the server to the local webserver. Gunicorn is also used to run our flask application.

Link to the App: http://food.azure.vsystems.online (VM Currently Turned Off)

## Application Breakdown

The construction of the application broken down into the architecture below:

![LinuxServer](https://github.com/rjones18/Images/blob/main/Untitled%20Diagram.drawio.png)


### Front-End

- HTML
- CSS (Bootrap)


### Back-End 

- [Python](https://www.python.org/) 
- [Flask (Python Framework)](https://flask.palletsprojects.com/en/1.1.x/)


### DNS

- [Azure DNS](https://azure.microsoft.com/en-us/services/dns/#overview)
- [GoDaddy](https://www.godaddy.com/)


### Deployment Platform

- Linux Server hosted in Microsoft Azure
