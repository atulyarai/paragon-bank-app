# Paragon Bank
> Banking Website built on Django designed with Bootstrap
## Demo:
![](screenshot/bank.png)
## Installation:
**1.Clone Repo**
```sh
git clone https://github.com/shyam999/ParagonBank.git
```
**2.Setup Virtualenv & Install Requirements**
```sh
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```
**3.Migrate Database**
```sh
python manage.py makemigrations
python manage.py migrate
```
**4.Run Server**
```sh
python manage.py runserver
```
