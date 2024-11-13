Flask File Upload and Access Project

This project is a simple web application built with Flask that allows users to upload files and access them from a list. It provides an HTML interface for file uploading and displays links to uploaded files.

## Features

 * Upload files to the server.
 * Display a list of uploaded files with links for easy access.
 * Serve files for download or viewing directly in the browser.

## Getting Started

## Prerequisites
 * Python 3.x installed on your system.
 * Flask library. Install it using

   pip install Flask

## Project Structure
project_folder/
├── app.py            # Main application file
├── uploads/          # Folder for uploaded files (created automatically)
└── README.md         # Project README file

## Running the Application

1.  ## Clone the repository (if using Git):

git clone https://github.com/AmriteshRaj123/web_Server_Private_IP_Convert_Into_Public_IP.git
cd web_Server_Private_IP_Convert_Into_Public_IP

2. ## Set up the environment:

 ** Create a virtual environment (optional but recommended)

python3 -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

## Install Flask
pip install Flask

3. ## Run the application:
python app.py

4. ## Access the app in your web browser:

* Go to http://localhost:8000 to view the file upload interface.

## Code Overview
The main application file, app.py, consists of:

## Routes:
/ (GET and POST): Displays the upload form and lists uploaded files.
/uploads/<filename> (GET): Serves the uploaded files for download or viewing.
Example HTML Template
The HTML template for file uploading and listing is embedded in the upload_page variable within app.py and contains:

A form for file upload.
A list of uploaded files with links to access them.
Folder Structure
Uploaded files are saved in the uploads folder, created automatically if it does not exist.

## Project Demo
* Upload Files
Choose a file using the file input form.
Click on the "Upload" button to upload the file to the server.
Access Uploaded Files
Uploaded files are listed with links that allow users to view or download them.

## Dependencies
Flask: Used for handling HTTP requests and serving the web application.


