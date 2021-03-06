# python-django-corey

This project has been made to follow along with:

- [Django Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p) _by Corey Schafer_

## Requirements

- Python latest version (in this case Python==3.7.3)
- Django latest version (in this case Django==2.2.5)
- Git with SSH keys configured

## Setting Up Environment

### Creating Virtual Environment and Installing Django

Navegante to your Dev folder and run these commands

```
> mkdir python-django-corey
> cd python-django-corey
python-django-corey> pipenv install django
```

### Confirming installation

```
> python -m django --version
2.2.5
```

### Configuring Github and Git

1. [Create a new repository in Github](https://help.github.com/en/articles/creating-a-new-repository)
2. Configure local Git and push to Github

```
echo "# python-django-corey" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:matheusmiyahira/python-django-corey.git
git push -u origin master
```

3. Open VS Code

```
DevEnv\python-django-corey> code .
```

### New Djnago Server

C:\Users\cardosm6\Documents\DevEnv\python-django-udemy> django-admin
C:\Users\cardosm6\Documents\DevEnv\python-django-udemy> django-admin startproject django_project
C:\Users\cardosm6\Documents\DevEnv\python-django-udemy> cd .\django_project\
C:\Users\cardosm6\Documents\DevEnv\python-django-udemy\django_project> code .

### Running Local Web Application

> python manage.py runserver
> Ctrl+C to stop the server

### Creating New Application

C:\Users\cardosm6\Documents\DevEnv\python-django-udemy\django_project> python manage.py startapp blog
