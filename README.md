# Admin Finder Tool

A simple Python script to find potentially sensitive admin pages on a website. This tool tests various common admin URLs and checks if any of them return a 200 HTTP status code (indicating they exist). It's designed for security professionals, penetration testers, or anyone who needs to identify potential admin areas of a website.

![image](https://github.com/user-attachments/assets/2dbabfd1-3be3-46dc-a194-5237e1c22aab)

## Features

- Iterates through a list of common admin paths.
- Sends GET requests to check if these paths exist.
- Reports URLs that return a 200 status code.
- Handles exceptions and errors gracefully, reporting any issues during the process.

## Prerequisites

Before running this script, you need to have Python 3.x installed along with the `requests` library. 

### Install Python 3

You can download and install Python from the official site:
- [Download Python](https://www.python.org/downloads/)

(![image](https://github.com/user-attachments/assets/09cb6a2c-96a9-4593-9518-a1c0ac32c990)


### Install the `requests` library

This tool uses the `requests` library to make HTTP requests. Install it by running:

```bash
pip install requests
```

## How to Run the Admin Finder Tool
## For Windows
Prerequisites:
Python: Make sure Python is installed on your Windows machine. If not, follow these steps:
Download Python from the official site: Download Python.
During installation, ensure you check the box that says "Add Python to PATH".
Steps:
Install Python (if not already installed):

Open Command Prompt (cmd) and type:
```bash
python --version
```
If Python is installed correctly, it will show the version. If not, download and install Python from the official site.

## Install the required dependencies:

Open Command Prompt and install the requests library:
```bash
pip install requests
```
## download zip file repository


Run the script:

Navigate to the folder where the script is located using the Command Prompt:



```bash
python admin_finder.py
```



## Running the Script on Ubuntu Linux
Prerequisites:
Python: Most Ubuntu systems come with Python pre-installed. You can verify by running:

```bash
python3 --version
```
## Install the requests library and clone repository:

```bash
sudo apt update
sdo apt install git
sudo apt install python3-pip
pip3 install requests
git clone https://github.com/xnoncywer/adminfinder.git
```
## now run the code
```bash
cd adminfinder
python3 adminfinder.py
```
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!EXPLOIT IT!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
