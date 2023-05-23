This repository is no longer being actively maintained.

### IdGenerator
This is a web application for creating ID cards for college students and faculty. It is developed using HTML, CSS, JQuery, Django Framework, Reportlab, and SQLite.

Users can enter the required details, and the application will generate a PDF version of the ID card. It provides features such as registration, editing, searching, deletion, template customization, and PDF generation for both students and faculty.

Local Installation (Debian)
Set up a virtual environment using virtualenv . (virtualenv).
Activate the virtual environment with source bin/activate.
Install Django 1.9 and Reportlab by running pip install Django==1.9 reportlab.
Apply the database migrations with python manage.py makemigrations.
Execute the migrations with python manage.py migrate.
Start the server with python manage.py runserver.



### Usage


1. Register Details

![Register Details][Demo Link](http://idgen.pythonanywhere.com/)(https://user-images.githubusercontent.com/8125643/110128626-06383480-7ded-11eb-892a-9a1baffe2177.png)

2. Edit Template as per need

![Edit Template](https://user-images.githubusercontent.com/8125643/110128771-31bb1f00-7ded-11eb-9239-cba6ef95dcd0.png)

3. View List of registered users

![List](https://user-images.githubusercontent.com/8125643/110128796-38499680-7ded-11eb-8bae-619842bf6a94.png)

4. Download PDF

![Download PDF](https://user-images.githubusercontent.com/8125643/110128817-3c75b400-7ded-11eb-8a05-61719c5858ce.png)



