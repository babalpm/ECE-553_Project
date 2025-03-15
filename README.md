# ECE-553_Project
ECampus System

# Dependencies
Note All versions listed are just what was tested. Other versions/programs may work.

### Python WebServer:
    -Python 3.10

### Pip Installs:
    -flask: 3.1.0
    -flask-cors: 5.0.1

### Html Frontend:
    -Firefox: 
    -Edge (Optional): 134.0.3124.66

# Startup
### Windows (No webhosting)
    1) execute PythonServerBackend\runServer.bat
    2) Open HtmlFrontend/index.html in a browser 

### Windows (Webhosting)
    1) execute PythonServerBackend\runServer.bat
    2) execute hostWebpage.bat
    3) In a browser enter http:localhost:8000/index.html

### Linux (No webhosting)
    1) execute PythonServerBackend/runServer.sh
    2) Open HtmlFrontend\index.html in a browser 

### Linux (Webhosting)
    1) execute PythonServerBackend/runServer.sh
    2) execute hostWebpage.sh
    3) In a browser enter http:localhost:8000/index.html

# Frontend Run Instructions
    1) Enter text into "Data to send:" and press Send data to verify data is sent to the backend. This button provides feedback if the message was received.
    2) Get user data button recives the json database file from the backend

# Notes
    -Initial WebServer and Html code from here: https://github.com/tmsdev82/basic-web-app-tutorial/tree/main