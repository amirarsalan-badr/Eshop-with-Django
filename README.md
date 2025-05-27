
# Dajngo Ecommerce Website

A complete ecommerce website which consists of user profiles and other modern features of an ecommerce website.


## Installation

Install the virtual environment on ubuntu

```bash
  virtualenv -p python3.8 <your-fav-env-name>
```
To activate your virtual environment

```
source <your-fav-env-name>/bin/activate
```

Clone the project

```
git clone git@github.com:amirarsalan-badr/Eshop-with-Django.git
```
Install packages and run the project

```
cd Eshop-with-Django/
pip install -r requirements.txt
```
### Apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create superuser (for admin access):

```bash
python manage.py createsuperuser
```

### Run the development server:

```bash
python manage.py runserver
```
