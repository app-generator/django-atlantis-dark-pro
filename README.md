# [Django Atlantis PRO](https://appseed.us/product/atlantis-dark-pro/django/)

**Django** starter styled with **[Atlantis Dark PRO](https://appseed.us/product/atlantis-dark-pro/django/)**, a premium `Bootstrap` KIT from `ThemeKita`.
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. 

> **NOTE**: This product `requires a License` in order to access the theme. During the purchase, a `GitHub Access TOKEN` is provided. 

- 👉 [Django Atlantis PRO](https://appseed.us/product/atlantis-dark-pro/django/) - `Product Page`
- 👉 [Django Atlantis PRO](https://django-atlantis-dark-pro.appseed-srv1.com/) - `LIVE Demo`
- 🚀 [Support](https://appseed.us/support/) via `Email` & `Discord`

<br />

## Features: 

- ✅ `Up-to-date Dependencies`
- ✅ `Design`: [Django Theme Atlantis](https://github.com/app-generator/django-admin-atlantis-pro) - `PRO Version`
- ✅ `Sections` covered by the design:
  - ✅ **Admin section** (reserved for superusers)
  - ✅ **Authentication**: `Django.contrib.AUTH`, Registration
  - ✅ **All Pages** available in for ordinary users 
- ✅ `Docker`
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`
  - [Go LIVE - Django Atlantis PRO](https://www.youtube.com/watch?v=M0lA_-6lc-g) - `video presentation`

<br />

![Django Atlantis PRO](https://user-images.githubusercontent.com/51070104/212669274-3eef24b4-7c19-4557-99c5-e24ae5b14a5b.png)

<br />

## Manual Build 

> 👉 Download the code  

```bash
$ git clone https://github.com/app-generator/django-atlantis-dark-pro.git
$ cd django-atlantis-dark-pro
```

<br />

> Export `GITHUB_TOKEN` in the environment. The value is provided by AppSeed during purchase. 

This is required because the project has a private REPO dependency: `github.com/app-generator/priv-django-admin-atlantis-pro`

```bash
$ export GITHUB_TOKEN='TOKEN_HERE'  # for Linux, Mac
$ set GITHUB_TOKEN='TOKEN_HERE'     # Windows CMD
$ $env:GITHUB_TOKEN = 'TOKEN_HERE'  # Windows powerShell 
```

<br />

> 👉 Install modules via `VENV`.


```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> 👉 Edit the `.env` using the template `.env.sample`. 

```env

# True for development, False for production
DEBUG=True

```

<br />

> 👉 Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> 👉 Create the Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> 👉 Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Screenshots

![Django Admin Atlantis PRO - Main Dashboard Page.](https://user-images.githubusercontent.com/51070104/213626540-300ee6e1-f051-449d-be54-0e8c9e07cd99.jpg)

<br />

> [Django Admin Atlantis PRO](https://appseed.us/product/atlantis-dark-pro/django/) - `Maps Page`

![Django Admin Atlantis PRO - Maps Page.](https://user-images.githubusercontent.com/51070104/213626614-0eb12373-f975-406c-a868-058e3cf24df3.jpg)

<br />

> [Django Admin Atlantis PRO](https://appseed.us/product/atlantis-dark-pro/django/) - `Charts Page`

![Django Admin Atlantis PRO - Charts Page.](https://user-images.githubusercontent.com/51070104/213626717-960c4545-bbce-4372-b7c9-09ea1cd5865d.jpg)

<br />

---
**[Django Atlantis PRO](https://appseed.us/product/atlantis-dark-pro/django/)** - Modern Admin Interface provided by **[AppSeed](https://appseed.us/)**
