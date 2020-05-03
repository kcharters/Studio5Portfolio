# Project1Portfolio
portfolio notes<br>
https://docs.djangoproject.com/en/3.0/intro/tutorial01/<br>
<br>
set uo virtual environment
- anaconda navigator
- environments
- create
- python 3.7 if not avaliable install
- click paly button 
- open terminal
- go to folder with project
 install djangoproject
- in folde project 
-pip install django
- check version python -m django --version
- if not 3.0 
- pip install --upgrade django==3.0.4

setting up local phpmyadmin <br>
run manage.py syncdb <br>
pip install mysqlclient <br>


include app to site <br>
python manage.py makemigrations polls<br>
you’re telling Django that you’ve made some changes to your models<br>
 (in this case, you’ve made new ones) <br>
and that you’d like the changes to be stored as a migration.<br>
