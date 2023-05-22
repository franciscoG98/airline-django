# Airline-django

This app war made with python and Django. It allows you to add flight, airports, passengers and users from de admin panel.

It consist in 2 applications, one called Flights, that have 3 models of data: airports (city and airport code), flights (origin, destination, and duration), passengers (first name, las name and flights). And its routes and views allow you to see all the information in a list displayed by an html file.

The Other application it is called Users and allow you to log in and logout, you can create users in the admin panel

## Scripts 
```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```

