# Project Create a Pic sharing Website for Friends

## Set Up
#### Install VENV
```bash
pip3 install virtualenv
virtualenv venv
```

#### Install Packages
```bash
source venv/bin/activate
pip3 install <package-name>
pip3 install django
deactivate
```

#### Start Project
```bash
django-admin startproject web1
```
```python
python3 manage.py runserver
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py startapp blog
python3 manage.py startapp mainpage
python3 manage.py startapp portfolio
```
