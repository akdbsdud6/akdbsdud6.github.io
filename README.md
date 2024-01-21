Introduction
This interactive parking map is a web application that helps users find and report available parking spots. It integrates a Python Flask backend with a frontend using HTML, CSS, and JavaScript.

Features
Interactive map interface with clickable buttons for parking lots.
Dropdown menus displaying parking lot names and available spots.
User-reporting feature for updating parking availability.

Technology Stack
Backend: Python, Flask
Frontend: HTML, CSS, JavaScript

Installation and Setup
To run this project locally, follow these steps:

Prerequisites
Python 3.6 or higher
Flask
Visual Studio Code (or another IDE with similar capabilities)
Live Server extension for Visual Studio Code (or equivalent setup)

Installation

Clone the repository:
git clone [repository URL]

Navigate to the project directory:
cd [project-directory]

Install Flask and other dependencies:
pip install -r requirements.txt

Running the Application
Run the Flask App
Open a terminal or command prompt.
Navigate to the directory containing dict.py.
Start the Flask server:
python dict.py

Run the Frontend
Open the directory containing your HTML files in Visual Studio Code.
Start the frontend using the Live Server extension or equivalent.
Connect Frontend to Backend
Ensure your frontend JavaScript fetch requests are pointed to your Flask server (e.g., http://localhost:5000/get_parking_data/Stevenson).
Test the Application
Access your frontend through the provided URL.
Interact with the frontend features and observe the corresponding activities on the Flask server.