# django_bgRemoverML
A Machine Learning Project integrated with Django to Remove Background from Image . 

## Installation:
- git clone https://github.com/FarjaalAhmad/django_bgRemoverML
- cd django_bgRemoverML
- pip3 install -r requirements.txt
- python3 setup.py
- python3 manage.py migrate
- python3 manage.py runserver

Site URL: http://localhost:8000

### Usage:
For API Usage
=============
Make a POST request to http://localhost:8000/upload with the Following parameters.
	
	image=[BASE64 ENCODED IMAGE HERE]
	
### To be Added Later:
- Design a Good Looking Frontend

### Known Bugs:
- <b>Memory Leak Issue.<b>
	Memory doesn't get released after Processing the Images. Memory Exhaustion cause the crash of server.

If someone can fix this bug, please fix this bug and make a Pull Request. Thanks <3


#### Contact: farjaalahmad[at]gmail.com
