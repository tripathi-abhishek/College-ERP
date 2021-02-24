# College-ERP
A college management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table.

## Installation

Python and Django need to be installed

```bash
pip install django
```

## Usage

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.
The username is their name and password for everyone is 'project123'.
Example usernames:
student- 'samarth'
teacher- 'trisila'

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'admin' and the above password.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.

**For more details regarding the system and features please refer the reports included.**

## Screenshots

### Teacher Page

![alt text](https://i.imgur.com/q04kWIY.jpg)

![alt text](https://i.imgur.com/wRSLe5Z.jpg)

![alt text](https://i.imgur.com/qdClDNy.jpg)

![alt text](https://i.imgur.com/KZuvv44.jpg)

![alt text](https://i.imgur.com/ITiezAy.jpg)

![alt text](https://i.imgur.com/b1JMGsA.jpg)

![alt text](https://i.imgur.com/wOHABcJ.jpg)

### Student Page

![alt text](https://i.imgur.com/iq6mGZv.jpg)

![alt text](https://i.imgur.com/i2cG6wY.jpg)

![alt text](https://i.imgur.com/it7YBdh.jpg)

![alt text](https://i.imgur.com/IjV7B45.jpg)

![alt text](https://i.imgur.com/7HlyPdD.jpg)

### Admin Page

![alt text](https://i.imgur.com/D4yjzGh.jpg)

![alt text](https://i.imgur.com/y1MYco1.jpg)

![alt text](https://i.imgur.com/77IuKio.jpg)
