# IE_Final_Project- 
Cinema tickets sale system

Created by Shakiba Ehteshami and Gita Shojaee

studentId : 970122680101 - 970122680031

# Clone and Run a Django Project from Github
### requirements
Github Desktop / Git Bash
Python 3

### To run Django prefer to use the Virtual Environment
Clone or download and issue the below commands in project root directory and open [http://localhost:3000](http://localhost:3000) in browser
```javascript
pip install virtualenv
```
### Making and Activating the Virtual Environment:
```javascript
virtualenv “name as you like”
source env/bin/activate
```
### Installing Django:
```javascript
pip install django
```
Now, we need to clone any Django project from Github.
After finishing the cloning part let’s move to the main Django run part.
### Install the project dependencies:
```javascript
pip install -r requirement.txt
```
### Make a demo project just to copy the SECRET KEY generated by Django.
To create follow the steps below:

1.open CMD and type django-admin startproject “name of the project”

2.Now go to the setting.py and copy the SECRET_KEY.

3.Navigate to the cloned folder and open the setting.py and paste the copied SECRET_KEY.

4.Then open the cmd in that folder and do the migration part and also create the superuser by the following commands.
```javascript
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```

5.Now the last thing is that just go to the cloned project and run the project by writing the following command in the CMD.

### Run
```javascript
python manage.py runserver
```
