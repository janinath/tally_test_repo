# TallyApp

This is a Django-based application designed to connect with Tally for importing and managing data. The app provides a minimal interface for importing Tally data and saving it in the Django database.

## Table of Contents
- [Setup](#setup)
- [Environment Details](#environment-details)
- [Running the Application](#running-the-application)
- [Dependencies](#dependencies)
- [License](#license)

## Setup

### 1. Clone the Repository
Clone the project to your local machine:
```bash
git clone https://github.com/your-manager/tallyapp.git
cd tallyapp


2. Create and Activate Virtual Environment
Creating the virtual environment:
Navigate to the folder containing the Django project (where manage.py is located).
Open the terminal or command prompt in the folder.
Run the following command to create a virtual environment

virtualenv env


Activating the virtual environment:
Navigate to the env folder

cd env/scripts

Open the command prompt in the scripts folder.
Activate the environment by running

activate

3. Install Dependencies
After activating the virtual environment, navigate back to the project folder (where manage.py is located) and install the required dependencies:

pip install -r requirements.txt

4. Apply Migrations
To set up the database, run the migrations:

python manage.py migrate


5. Running the Application
Once all dependencies are installed, and the environment is activated, you can start the development server:

python manage.py runserver

The application will be available at http://127.0.0.1:8000/