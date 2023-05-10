
README

Introduction

This is a Python script that uses Selenium and xlrd libraries to search for the availability of domain names on Registro.br website and writes the results in a text file.

Prerequisites
Before running the script, you need to have Python 3.x installed on your machine. You also need to have the following Python libraries installed:

selenium
xlrd

You also need to have Google Chrome browser installed on your machine and the path to the ChromeDriver executable file needs to be updated in the script.

Installation

Install Python 3.x
Install selenium and xlrd libraries using pip command:
Copy code
pip install selenium
pip install xlrd

Download the ChromeDriver executable file from https://chromedriver.chromium.org/downloads and save it in a folder on your machine.
Update the path to the ChromeDriver executable file in the script.

Usage

Prepare an Excel file with a list of domain names you want to search for availability.
Update the path to the Excel file in the script.
Run the script using the command prompt or any IDE that supports Python.

Output

The script will write the results to a text file named "resultado.txt". The file will be saved in the same folder as the script.

Note
This script uses Selenium to automate web browsing, which means it controls a browser programatically. Make sure that you don't have any sensitive information opened in your browser while the script is running.
