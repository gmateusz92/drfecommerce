# Packages

pip freeze
pip freeze > requirements.txt
django install r requirements.txt
pip install python-dotenv
pip install djangorestframework

# Commands

django-admin straproject drfcommerce
./manage.py runserver

from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())

# pytest

pytest -h #print options _and_ config file settings