# Django Simple E-Commerce Website with Payment
This is a simple e-commerce website built with Django (Python) 

Modules

Admin Users
1. Manage Category (Add, Update, Filter and Delete)
2. Manage Products (Add, Update, Filter and Delete)
3. Manage Users (Update, Filter and Delete)
4. Manage Orders (View and Process)

 Non-Registered Users 
1. View Products (Can filter based on category)
2. Explore Product Details and Related Products


Registered Users 
1. All ot Non-Registered Users
2. Add to Cart
3. Pay with PayPal or Debit/Credit Card and Order
4. See the Order Status
5. See Order History
6. Update Profile 
7. Change Password
8. Reset Password





### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

clone this project use this link ---- https://github.com/Mani-ML-Developer/Jewellery-Website.git


```python
$  pip install -r requirements.txt
```



- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```
*No need to change on Mac.*



Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```


Create Super User (Admin)

Command for PC:
```
$  python manage.py createsuperuser
```

Command for MAC:
```
$  python3 manage.py createsuperuser
```
Then Add Email, Username and Password



