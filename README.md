# Simple Web Application

This is a simple web application using [Python Flask](http://flask.pocoo.org/). 
This is used in the demonstration of developments.
  
  Below are the steps required to get this working on a base linux system.
  
  - Install all required dependencies
  - Install and Configure Web Server
  - Start Web Server
   
## 1. Install all required dependencies
  
  Python and its dependencies

    apt-get install -y python python-setuptools python-dev build-essential python-pip

   
## 2. Install and Configure Web Server

Install Python Flask dependency

    pip3 install -r requirements.txt

- Copy app.py or download it from source repository

## 3. Start Web Server

Start web server

    FLASK_APP=app.py flask run --host=0.0.0.0 --port=8080
    
## 4. Test

Open a browser and go to URL

    http://<IP>:8080                        => Hello World!
    http://<IP>:8080/api                    => {status: ok}
