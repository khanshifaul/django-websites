# Django Cheatsheat

## pip3
install pip3 on linux
```
sudo apt install python3-pip
```
check pip3 version
```
pip3 --version
```

## virtualenv
install virtualenv on linux using apt
```
sudo apt-get install python-virtualenv virtualenv
```
install virtualenv using pip3
```
pip3 install virtualenv
```
create an environment
```
virtualenv -p python3 envgv1
```
activate the environment
```
source bin/activate
```
deactiveate the environment
```
deactivate
```

## django
```
git clone git://github.com/django/django django-dev
```
```
pip3 install -e django-dev
```
```
django-admin --version
```
```
django-admin startproject proyect
```
```
python manage.py createsuperuser
```
```
python manage.py startapp name
```
```
python manage.py runserver
```
```
pip install -r requirements.txt
```
```
python manage.py shell
```
```
python manage.py collecstatic
```
