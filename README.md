Google Cloud Functions Course
Starting a Project
To start a new project in Google Cloud Platform (GCP), you can either:

Visit the Firebase Console to create the project.
Alternatively, create it directly from the Google Cloud console.
Creating a Virtual Environment
To set up a Python virtual environment for the project:

Install Python 3 virtual environment: Run the following command to install the necessary package for Python 3 virtual environments:

bash
Copy code
sudo apt install python3-venv
Set up the virtual environment: To create a virtual environment named venv, use this command:

bash
Copy code
python3 -m venv venv
Activate the virtual environment: Once the virtual environment is created, activate it with:

bash
Copy code
source venv/Scripts/activate
Installing Dependencies
To install the required dependencies for the project:

Create a requirements.txt file: List all the dependencies your project needs in the requirements.txt file.

Install dependencies: Use the following command to install the packages from the requirements.txt file:

bash
Copy code
pip install -r requirements.txt