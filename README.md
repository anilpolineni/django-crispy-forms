# Django-Crispy-Forms
you will build a simple example Django application with a form styled with Bootstrap


# What is Django-Crispy-Forms

* By using django-crispy-forms, a popular package that makes it easy for Django developers to create beautiful forms easily and without re-inventing the wheel.

* you'll also be using Bootstrap 4—the latest version of the most popular CSS and HTML framework for building HTML interfaces—to style the form.

* The django-crispy-forms enables you to quickly add and render Bootstrap 4 styled forms with a few lines of code.

## Prerequisites

* A recent version of Python 3 (3.6 is the latest),
+ A basic knowledge of Python,
- A working knowledge of Django.

## Creating a Django Project & Application

* After installing Django, you need to create a project  using django

### Project Create


````
django-admin startproject dempproject
````

* Next, create an application using manage.py, you can name it accounts

### App Create

````
cd demoproject
````

````
django-admin startapp accounts
````
-       (or)

````
python manage.py startapp accounts
````

#### Next, you need to add accounts in the INSTALLED_APPS array inside the settings.py file of your project.

```
Installing & Setting up django-crispy-forms
````


------------------------------------------

* Before adding anything else, let's install the django-crispy-forms application by using pip:

````
pip install django-crispy-forms
````


+ Next, as always, you need to add django-crispy-forms into the INSTALLED_APPS array in the setting.py file

--------------------------------------------
```INSTALLED_APPS = [

    'accounts(appname)',
    
    'crispy_forms',
    
         ]
````
