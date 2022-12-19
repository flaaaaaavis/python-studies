# python-studies

<!-- https://github.com/flaaaaaavis/python-studies -->
<br/>

### Run on bash:  

#### &ensp; &ensp; &ensp; &ensp; create virtual envirement:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;py -m venv venv
#### &ensp; &ensp; &ensp; &ensp; activate virtual envirement:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;source venv/Scripts/activate

#### &ensp; &ensp; &ensp; &ensp; install django:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;py -m pip install Django

#### &ensp; &ensp; &ensp; &ensp; install other dependencies:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;pip install black ipdb pycodestyle

#### &ensp; &ensp; &ensp; &ensp; install django rest framework:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;pip install djangorestframework

#### &ensp; &ensp; &ensp; &ensp; create / update dependencies archive:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;pip freeze > requirements.txt

#### &ensp; &ensp; &ensp; &ensp; atualizar o SQL Lite:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;py manage.py makemigrations  
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;py manage.py migrate


#### &ensp; &ensp; &ensp; &ensp; create project:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;django-admin startproject nome-do-project .

#### &ensp; &ensp; &ensp; &ensp; create apps:
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;python manage.py startapp nome-do-app  
OBS: adicionar o nome do app ao INSTALLED_APPS, no settings.py do project

#### &ensp; &ensp; &ensp; &ensp; run server: 
&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;py manage.py runserver&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;  =====> para sair:  ctrl + ^C  
<br/>

### To run Python Shell:  

&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;py manage.py shell&ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;  =====> para sair:  quit()
