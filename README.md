# Django-Human-Resources-Management-System

This app is meant to be used by HR manager to manage their hrm records:
employee data
staff
results and
finances.

It currently doesn't allow employees/staff to login.
Solely, it's expected to be used on a single machine or online for managers only.

Multi Tenant schema actively under development.




## Usage
It's best to install Python projects in a Virtual Environment. Once you have set up a VE, clone this project

```bash
git clone 
```
Then

```bash
cd Human-Resources-Management-System
```
Run

```python
python -m venv venv   #install virtual enviroment
venv\scripts\activate   #activate virtual enviroment venv
pip install -r requirements.txt #install required packages
python manage.py migrate # run first migration
python manage.py runserver # run the server
```
Then locate http://172.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin123
```

## Roadmap
To build a fully fledged HR management system.

## Coding Standards
```bash
isort .
black .
```

## Test
```base
python manage.py test
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Actively under development
