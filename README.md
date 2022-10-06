# Password Manager Website
- Html
- CSS
- Django
- Python

Currently, it uses the master account password to encrypt the stored passwords **twice.** Even in the event of a large data breach in production, where all passwords are leaked, the passwords would still be **very** secure. 


## How to set up project (Windows CMD)
  
```
###### install the necessary python packages
```
pip install requirements.txt
```
###### setup SQLite database
```
python manage.py migrate
```
###### start the test server 
```
python manage.py runserver
```

