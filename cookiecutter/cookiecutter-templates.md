# Cookiecutter
https://medium.com/worldsensing-techblog/project-templates-and-cookiecutter-6d8f99a06374
Cookiecutter is a CLI tool (Command Line Interface) to create an application boilerplate from a template. It uses a templating system — Jinja2 — to replace or customize folder and file names, as well as file content.

- can be used with any programming language

## Why?
- We use Cookiecutter to save time constructing a new repository, to avoid forgetting mandatory files like Readme or Changelog; and to lower the entry level to new collaborators
- We also use it as a way to enforce standards: you can see it as an invitation to the developer to follow the established rules

## How?
- Cookiecutter can be used either with a Git repository, with a folder or even a Zip file

```
pip install — user cookiecutter
cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git
```

## Available Templates
The best place to start searching for specific and ready to use cookiecutter template is Github search. Just type cookiecutter and you will discover over 4000 related repositories.
https://github.com/search?q=cookiecutter&type=Repositories

We also recommend you to check related GitHub topics. For general search use cookiecutter-template. For specific topics try to use cookiecutter-yourtopic, like cookiecutter-python or cookiecutter-datascience. This is new GitHub feature, so not all active repositories use it at the moment.
https://github.com/topics/cookiecutter-template

Some nice templates:
- https://github.com/drivendata/cookiecutter-data-science
- https://github.com/cookiecutter-flask/cookiecutter-flask
- https://github.com/karec/cookiecutter-flask-restful
- Maintained by cookiecutters team (https://cookiecutter.readthedocs.io/en/1.7.2/README.html#a-pantry-full-of-cookiecutters)
	- https://github.com/audreyr/cookiecutter-pypackage: @audreyr’s ultimate Python package project template.
	- https://github.com/pydanny/cookiecutter-django: A bleeding edge Django project template with Bootstrap 4, customizable users app, starter templates, working user registration, celery setup, and much more.
	- https://github.com/pytest-dev/cookiecutter-pytest-plugin: Minimal Cookiecutter template for authoring pytest plugins that help you to write better programs. (Installable PyPI package)