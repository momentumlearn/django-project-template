# Django Project Template

This project was generated from the Momentum Django project template. This template sets up some minimal changes:

- [django-extensions](https://django-extensions.readthedocs.io/en/latest/) and [django-debug-toolbar](https://django-debug-toolbar.readthedocs.io/en/latest/) are both installed and set up.
- [django-environ](https://django-environ.readthedocs.io/en/latest/) is set up and the `DEBUG`, `SECRET_KEY`, and `DATABASES` settings are set by this package.
- There is a custom user model defined in `users.models.User`.
- There is a `templates/` and a `static/` directory at the top level, both of which are set up to be used.
- A `.gitignore` file is provided.
- Pipenv is used to manage dependencies.

## Using this template

In an empty directory, run:

```
django-admin startproject --template=https://github.com/momentumlearn/django-project-template/archive/master.zip --name=Pipfile project .
pipenv install
cp project/.env.sample project/.env
./manage.py migrate
```

If you want to use another directory for your project directory, replace `project` above with the name of your directory.
