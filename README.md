# Polls 

> 🖱️ A public site that lets people view polls and vote in them. [Django Documentation](https://docs.djangoproject.com/en/2.2/intro/tutorial01/)

## 🚀 Stacks
This project was developed with the following technologies:

- [Python](https://www.python.org/doc/)
- [Django](https://docs.djangoproject.com/en/2.2/)
- [PyCharm](https://www.jetbrains.com/pt-br/pycharm/download/#section=windows) 
- [SQLite](https://www.sqlite.org/docs.html)

## :up: APP Features

## :construction_worker: How to run?
```bash
git clone https://github.com/JardelDeveloper/app-polls-django.git
```

## ⚒ Build APP
```bash
# Build Project
$ django-admin startproject mysite
# Build App
$ python manage.py startapp polls
```

## 🗃️ Store and Migrate the Database
```bash
# Store model changes in a migration
$ python manage.py makemigrations
# Run migrate
$ python manage.py migrate
```

## :computer: Run Polls
```bash
# Access the directory 
$ cd mysite
# Install Dependencies (VENV)
# Run Polls app
$ python manage.py runserver
```
Go to http://127.0.0.1:8000/polls/ 

## 🔐 Run Admin Polls
```bash
# Access the directory 
$ cd mysite
# Create Super User
$ python manage.py createsuperuser
# Run Admin app
$ python manage.py runserver
```
Go to http://127.0.0.1:8000/admin/

## 🤔 How to contribute?
```bash
# Make a Fork this repository;
# Create a branch with your feature: 
git checkout -b my-feature;
# Make commit to your changes: 
git commit -m "feat: my new feature";
# Make a push to your branch: 
git push origin my-feature;
```
After the merge of your pull request is done, you can delete a branch of yours.

## :wrench: Issues
Feel free to **file a new issue** with a respective title and description on the the [Polls](https://github.com/JardelDeveloper/app-polls-django/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**.

## :memo: License
Released in 2020 :closed_book:

This project is under the MIT license. See the [LICENSE](https://github.com/JardelDeveloper/app-polls-django/blob/master/LICENSE) for more details.

Made with :green_heart: by Jardel Cunha.

Give :star: if this project helped you!