[Project Structure
When installing Django globally or in a virtual environment, Python recommends using isolated environment libraries and other dependencies required for a particular application.

Python's standard library contains the venv module. 

It installs a command-line utility called Django-admin in the system path and is located in the scripts folder of your current Python environment.

As the name suggests, you use the django-admin utility to perform various administrative tasks. 

These tasks include creating the project and app, performing  migrations to generate database tables, whose structure matches data models, and running a development server.

What is a project?
When you set out to build a modular, extensible and scalable web application, you need an arrangement that controls the standard features of its various sub-modules.

A Django project is a Python package containing the database configuration used by various sub-modules (Django calls them apps) and other Django-specific settings.

Use the startproject command of Django-admin as follows:   
(djenv) C:\djenv>django-admin startproject demoproject 
The startproject is Django’s default project template. It creates the following file structure in the Python environment:  ](https://www.coursera.org/learn/django-web-framework/supplement/Ahqrc/project-structure
https://www.coursera.org/learn/django-web-framework/supplement/rDp6w/app-structures)
