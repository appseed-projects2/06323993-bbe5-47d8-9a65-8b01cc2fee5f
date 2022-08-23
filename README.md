# [Argon Dashboard](https://appseed.us/product/argon-dashboard/) Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Argon Dashboard](https://appseed.us/product/argon-dashboard/)**, a modern `Bootstrap 5` dashboard design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).
  
<br />

> Built with [Argon Dashboard Generator](https://appseed.us/generator/argon-dashboard/)

- 👉 [Flask Argon Dashboard](https://appseed.us/product/argon-dashboard/flask/) - product page
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
- ✅ [PRO Version Available](https://appseed.us/product/argon-dashboard-pro/flask/) - `enhanced UI` and more `features` 

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Argon Dashboard - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172859049-25ef7546-44e5-4234-95cb-5925b7ebd9be.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

<br />

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />


## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/06323993-bbe5-47d8-9a65-8b01cc2fee5f.git
$ cd 06323993-bbe5-47d8-9a65-8b01cc2fee5f
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Argon Dashboard is a premium Bootstrap Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, Argon Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Argon Dashboard PRO Flask](https://appseed.us/product/argon-dashboard-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Argon Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172859139-621325fd-a235-4019-a75d-64a9a978da29.png)

<br />

---
[Argon Dashboard](https://appseed.us/product/argon-dashboard/) Flask/Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
