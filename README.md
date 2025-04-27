# Applied_Network_Protocol_Analysis
This project involves creating a Pyhton script designed to perform a brute force attack on a HTTP application running on a specified port. The script automates multiple PIN code submissions and monitors the server's responses to identify when the correct PIN has been entered. A crucial part of the setup involved determining the server's IP address, port, and required request parameters.

How to run the project

Starting the Server

Launch the provided .exe file to initialize the server.

Open a web browser and navigate to http://127.0.0.1:8888.

The server will be ready to receive PIN input once the page loads.

Running the Python Script

Ensure Python is installed on your system

Navigate to the directory and run the script using the terminal

python brute_force.py

The Script will attempt every 3 digit PIN and show the progress in the terminal.

I used wiresgark to monitor the network traffic while running the .exe.
