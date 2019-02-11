# aws-ubuntu-instance


A README file is included in the GitHub repo containing the following information: IP address, URL, summary of software installed, summary of configurations made, and a list of third-party resources used to complete this project.

## IP Address: 3.16.89.76

## URL: http://ec2-3-16-89-76.us-east-2.compute.amazonaws.com

## Software installed:
This is an Ubuntu 18 machine running an Apache web server. The server is serving a Python Flask application which connects to a SQLAlchemy database.

## Configurations:
* Grader user added with root access
* Root login disabled
* Ports 123(NTP), 80(HTTP), and 2200(SSH) are only ports open
* Default SSH port 22 disabled
* SSH login enforced
* Serves Python Flask application
* Stores data in SQLAlchemy database

## Third Party Resources Consulted:
* Main tutorial followed to get server running initally: http://terokarvinen.com/2016/deploy-flask-python3-on-apache2-ubuntu
* Transferring files to AWS instance: https://angus.readthedocs.io/en/2014/amazon/transfer-files-between-instance.html
* Digital Ocean
* Stack Overflow
* Stack Exchange - Ask Ubuntu
* Udacity Forums
* AWS Documentation
* GitHub Forums
* Mr. Graham Dumpleton
