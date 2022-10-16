## About
### Real Estate Multi-page Application with Admin area
- Search the property using keywords and search filters <br>
- Get detailed information about chosen property <br>
- Pagination implemented <br>
- Login/Logout <br>
## Setup

1. The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/AnastasiaLunina/django_real-estate.git
$ cd realestate
```

2. Create a virtual environment to install dependencies in and activate it:

```sh
$ python3 -m venv ./env

# Mac/Linux
$ source env/bin/activate

# Windows
venv\Scripts\activate.bat

# Exit venv
deactivate
```
3. In settings.py change password for PostrgreSQL. 

4. Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```

5. Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd project
(env)$ python manage.py runserver
```
6. And navigate to `http://127.0.0.1:8000/