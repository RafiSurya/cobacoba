# Project Elisa

<p align="center">
<a href="https://drive.google.com/uc?export=view&id=1IoEeI_jrky1YI7cHQGa0X00xc5IrrfLr"><img src="https://drive.google.com/uc?export=view&id=1IoEeI_jrky1YI7cHQGa0X00xc5IrrfLr" style="width: 300px; max-width: 50%; height: auto" title="Click to enlarge picture" />
  </p>
  
### Hardware requirements
  * 2 Core
  * 3 GB RAM
  * Database connection 20 - 50
  * 2 Hosting
  * 1 Database
  
  
### Software requirements
  * Pyhton 3.8
  * Php 7.4
  
### Chatbot Dashboard System Configuration
  * Install library `composer install`
  * Generating app_key `php artisan key:generate`
  * Create database and migrate database `php artisan migrate`
  
### Chatbot Engine Configuration
  * Create virtual enviroments `conda create -n botengine python=3.8`
  * Install library `pip install - r requirements.txt`
  * Open webhook.py and setting token with app_key Laravel and resources_url
  * Set main code `set FLASK_APP=webhook.py`
  * Run code `flask run`
