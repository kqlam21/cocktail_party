﻿# Cocktail Party

## Table of Contents

* [Overview](#overview)
* [Tech Stack](#tech-stack)
* [Features](#features)
* [Setup/Installation](#setup)
* [About the Developer](#developer)
 
## <a name="overview"></a>Overview
Discover the perfect cocktails for any occasion. <a href="https://www.cocktailparty.fun/" target="_blank">Cocktail Party </a>features 500+ recipes to view, favorite, or add to personalized lists. With Cocktail Party, you will be clicking then sipping in no time! Cheers!

Watch my demo here: <a href="https://vimeo.com/kqlam21/cocktailparty">Cocktail Party Demo</a>
<br>

## <a name="tech-stack"></a>Tech Stack
__Front End:__ HTML5, Jinja2, JavaScript, jQuery, AJAX, Bootstrap, CSS<br>
__Back End:__ Python, Flask, PostgreSQL, SQLAlchemy<br>
__APIs:__ TheCocktailDB
<br/>

## <a name="features"></a>Features

Browse by top cocktails, cocktails by name, popular liquor types, or recommended cocktails based on your favorites:
<br><br>

<p align="center">
<img src="/static/videos/browse.gif">
<br/><br/>
 </p>

If you’re looking for something more specific, there’s a keyword search bar to help you narrow it down:
<br><br>

<p align="center">
<img src="/static/videos/search.gif">
<br/><br/>
 </p>

Once you've found a cocktail you like, you can add it to your favorites or any event that you've created:
<br><br>

<p align="center">
<img src="/static/videos/cocktail.gif">
<br/><br/>
 </p>

In your profile, create your own event to keep track of cocktails you’ve saved so you can quickly look them up and serve them at your next event:
<br><br>

<p align="center">
<img src="/static/videos/profile.gif">
<br><br>
 </p>

## <a name="setup"></a>Setup/Installation

### Prerequisites:

- Python3
- PostgreSQL

### Run Cocktail Party on your local computer:

Clone repository:
```
$ git clone https://github.com/kqlam21/cocktail_party.git
```
<br>

Create and activate a virtual environment inside your cocktail_party directory:
```
$ virtualenv env
$ source env/bin/activate
```
<br>

Install dependencies:
```
$ pip3 install -r requirements.txt
```
<br>

Create database 'cocktails':
```
$ createdb cocktails
```
<br>

Run model.py in terminal to create database tables:
```
$ python3 model.py
Connected to db & created tables.
```
<br>

Run the app from the command line:
```
$ python3 server.py
```
<br>

Visit localhost:5000 on your browser to start clicking and sipping!
<br><br>

## <a name="developer"></a>About the Developer

Accountant-turned-developer, Kerry is a curious, collaborative problem solver always in pursuit of the most thoughtful and efficient solutions. 

Learn more about Kerry on her <a href="https://www.linkedin.com/in/kerrylam/" target="_blank">LinkedIn.</a>
