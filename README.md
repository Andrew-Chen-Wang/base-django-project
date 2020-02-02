# Base Django Project
Minimal Django Project with Registration for easy re-use during testing.

---
## The code itself
Much of this code comes from my [Stripe Subscription](https://github.com/Andrew-Chen-Wang/django-stripe-subscription) test project with Django. So you will find the word "Stripe" scattered around the code.

Additionally, this is only a base! For personal perference, **I have disabled all AUTH_PASSWORD_VALIDATORS when DEBUG is True.**

I actually HIGHLY recommend you use cookiecutter-django (with Docker) for large scale applications. Otherwise, enjoy my base project setup.

---
## Setup
You can set this code up by:

1. Cloning or downloading this respository.
2. Creating a virtual environment.
3. `Pip install django`
  - Note: the django that this uses is Django==3.0.2 so some dependencies can break. 

---
## Changelog
All notable changes to this project will be documented in this file.

### [0.0.1] - 2020-02-01
#### Added
- Entire Django project
- Registration added with minimal template setup
- A little bit of Stripe code :P Will delete later.
#### Changed
- Made AUTH_PASSWORD_VALIDATORS an empty list if `DEBUG=True`

---
## LICENSE
License: MIT License
Attribution is not necessary.
