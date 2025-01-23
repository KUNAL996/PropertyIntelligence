# PropertyIntelligence
Project Overview
A Flask-based web application that predicts house prices and rental rates using machine learning, allowing users to estimate property values by inputting various property attributes.
Features

Price prediction for buying and renting
Interactive web interface
Multiple input parameters including:

BHK count
Location features
Proximity to amenities
Area type (urban/rural)


Dependency graph showing feature correlations

Technologies Used

Python
Flask
Machine Learning
Pickle (model serialization)
HTML
Bootstrap

Setup and Installation
Prerequisites

Python 3.x
pip

Installation Steps

Clone the repository
Install dependencies:
Copypip install flask pickle

Run the application:
Copypython main.py


How to Use

Select "Buy" or "Rent"
Fill out the property details form
Get instant price/rent prediction

Project Structure

main.py: Flask application core
templates/: HTML templates
static/: CSS and images
model.pkl: Serialized machine learning model

Model Features
Predicts property values based on:

Swimming pool presence
Transportation proximity
School/hospital distances
Park availability
Tax range
Area type
And more...

Visualization
Includes a dependency graph showing correlations between features and property prices.

[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)
