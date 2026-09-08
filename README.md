# Django Practice

My hands-on Django learning repository. Each directory captures a small step in learning how Django projects and apps are structured.

## Progress So Far

- Set up Django projects with Django 6.1.1 and Python 3.14.
- Created `Test-Project` and ran Django's initial database migrations.
- Created `HelloWorld-Project` with the standard Django project files.
- Created a `pages` app inside `HelloWorld-Project`.
- Registered the `pages` app in `INSTALLED_APPS`.
- Added a `.gitignore` entry for VS Code settings.

## Projects

| Directory | Current state |
| --- | --- |
| `Test-Project` | Initial Django project setup with a SQLite database and initial migrations. |
| `HelloWorld-Project` | Django project with a registered `pages` app, ready for views, URL routes, templates, and models. |

## Tech Stack

- Python 3.14
- Django 6.1.1
- SQLite
- Pipenv

## Run a Project

Install the dependencies and start Django's development server from the project you want to explore:

```bash
cd HelloWorld-Project
pipenv install
pipenv run python manage.py runserver
```

For the first project, replace `HelloWorld-Project` with `Test-Project`.

## Next Steps

- Add a page view and connect it to a URL.
- Create and render a template.
- Define a model, create migrations, and use the Django admin.
