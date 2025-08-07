# Network-WEB-Port-scanner
A simple network port scanner

Network WEbB Port Scanner
A simple network port scanner web application built with Python (Flask) for the backend and HTML/CSS/JavaScript for the frontend. This tool allows you to scan a range of ports on a target host to check which ports are open or closed.

Features
Scan a range of ports on any IP address or hostname.
Displays open and closed ports in a user-friendly web interface.
Uses multithreading for faster scanning.
Requirements
Python 3.6 or higher
Flask


Installation
Clone the repository:

bash

Copy
git clone https://github.com/Oko-max/Network-WEB-Port-scanner.git
cd network-port-scanner
(Optional but recommended) Create and activate a virtual environment:

bash

Copy*
python -m venv venv
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
Install dependencies:

bash

Copy*
pip install flask
Usage
Run the Flask application:

bash

Copy
python app.py
Open your web browser and navigate to:


Copy
http://127.0.0.1:5000/
Enter the target host/IP and port range, then click Start Scan.

View the scan results displayed on the page.
