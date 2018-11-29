# django-logging

This project contains the code for a Scalyr article on logging in the
Django framework written by yours truly.

The following will enable you to get up and running quickly assuming a sane
Python environment:

```
$ git clone git@github.com:caseydunham/django-logging.git
$ cd django_logging
$ python3 -m virtualenv env
$ pip install -r requirements.txt
$ cd app
$ python manage.py runserver
```

Point your browser at http://localhost:8000 and you should be greeted with
the following:

![Browser hello message](images/browser.png)
