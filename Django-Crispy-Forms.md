# Django-Crispy-Forms
* you will build a simple example Django application with a form styled with Bootstrap


# What is Django-Crispy-Forms

* By using django-crispy-forms, a popular package that makes it easy for Django developers to create beautiful forms easily and without re-inventing the wheel.

* you'll also be using Bootstrap 4—the latest version of the most popular CSS and HTML framework for building HTML interfaces—to style the form.

* The django-crispy-forms enables you to quickly add and render Bootstrap 4 styled forms with a few lines of code.

## Prerequisites

* A recent version of Python 3 (3.6 is the latest),
+ A basic knowledge of Python,
- A working knowledge of Django.


````
django-crispy-forms supports Django 2.2 and 3.0 with Python 3.5+.

````

## Creating a Django Project & Application

* After installing Django, you need to create a project  using django

### Project Create


````
django-admin startproject demoproject
````

* Next, create an application using manage.py, you can name it accounts

### App Create

````
cd demoproject
````

````
django-admin startapp student
````
     (or)

````
python manage.py startapp student
````

#### Next, you need to add accounts in the INSTALLED_APPS array inside the settings.py file of your project.

````
Installing & Setting up django-crispy-forms
````


____

* Before adding anything else, let's install the django-crispy-forms application by using pip:

````
pip install django-crispy-forms
````


+ Next, as always, you need to add django-crispy-forms into the INSTALLED_APPS array in the setting.py file


````
INSTALLED_APPS = 
[

    'student',(appname)
    
    'crispy_forms',
    
         ]
````

### Since django-crispy-forms supports multiple styles, you also need to specify the CSS framework you want to use in your forms.

* You can do that by using the **CRISPY_TEMPLATE_PACK**  setting in the settings.py file


```
CRISPY_TEMPLATE_PACK = 'bootstrap4'
```

* That's all what you need for installing and setting up django-crispy-forms.

____





