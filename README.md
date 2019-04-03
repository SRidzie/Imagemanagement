# Installations 

Install using pip, including any optional packages you want...

pip install djangorestframework
pip install markdown       # Markdown support for the browsable API.
pip install django-filter  # Filtering support
...or clone the project from github.

git clone https://github.com/encode/django-rest-framework
Add 'rest_framework' to your INSTALLED_APPS setting.

INSTALLED_APPS = (
    ...
    'rest_framework',
)
