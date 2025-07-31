**Accessible Transport Scheduler (ATS)**
The Accessible Transport Scheduler (ATS) is a desktop application designed to connect passengers with accessibility needs to drivers with suitable vehicles. It provides a platform for scheduling, managing, and tracking rides, with separate interfaces for passengers, drivers, and administrators.

The application is built with Python using the Flet framework for the user interface and MongoDB for the database.

**Setup and Installation**
Follow these steps to get the application running on your local machine.

1. Prerequisites
Make sure you have the following installed:

Python 3.3 or newer.

pip (Python's package installer).

2. Project Files
Place the following files in the same directory:

**ATSver1.0.py (the main application script)
.env
requirements.txt**

3. Environment Variables
This project requires API keys and a database connection string to function so make to open the main application file within the same directory as .env

4. Install Dependencies
Create the requirements.txt file in your project directory and paste the content below into it.
Open a terminal or command prompt in your project directory.
It is highly recommended to create a virtual environment to manage dependencies:

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

**Install all the required packages using pip:**
pip install -r requirements.txt

Running the Application
Once the setup is complete, you can run the application:

Make sure your terminal is in the project directory and the virtual environment is activated.

Run the main Python script:

python ATSver1.0.py

The application window should now open.
