# Python_FlaskMemeWebsite

# Memes Website

A simple Flask-based web application that fetches a random meme from an API and displays it with its description. The website automatically refreshes every 10 seconds to show a new meme.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files Overview](#files-overview)
- [License](#license)

## Description

This project uses Flask, a lightweight Python web framework, to create a simple meme-fetching web application. The application calls an external API to retrieve a random meme and displays it along with its description. The meme and its description are shown on the homepage, and the page refreshes every 10 seconds to display a new meme.

### Technologies Used
- **Python 3.x**
- **Flask** - Web framework
- **Requests** - For making API requests
- **Jinja2** - Templating engine used by Flask
- **HTML/CSS** - Frontend for displaying memes

## Features

- Fetches a random meme from an API.
- Displays the meme image along with its description.
- The page automatically refreshes every 10 seconds to show a new meme.
- Fully responsive for different screen sizes.

## Installation

Follow the steps below to set up the project locally.

### 1. Clone the repository

Clone this repository to your local machine using the following command:

bash
git clone https://github.com/yourusername/memes-website.git

2. Set up a virtual environment

It is recommended to use a virtual environment to manage project dependencies. To create and activate a virtual environment, run the following commands:

    On Windows:

python -m venv venv
venv\Scripts\activate

On macOS/Linux:

    python3 -m venv venv
    source venv/bin/activate

3. Install dependencies

Once the virtual environment is activated, install the project dependencies from the requirements.txt file using pip:

pip install -r requirements.txt

Usage
Running the Application

After installing the dependencies, you can start the Flask application by running the following command:

python meme_flask.py

The application will start a server on http://127.0.0.1:5000/ (or 0.0.0.0:5000 for network access), and you can visit it in your browser.
Refreshing the Page

The webpage will automatically refresh every 10 seconds and load a new random meme from the API.
Viewing the Meme

The meme is displayed with a maximum width and height of 500px, ensuring it fits well within the browser window. Below the image, the description of the meme (from the subreddit) is shown.

Files Overview
1. meme_flask.py
This is the main Flask application script that fetches the meme from the API and serves the page.

2. meme_index.html
This is the HTML template used to display the meme and its description. The page will auto-refresh every 10 seconds to show a new meme.

3. requirements.txt
This file lists all Python dependencies required to run the project.