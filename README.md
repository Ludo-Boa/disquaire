# disquaire

Project developed by following the OpenClassRoom course on Django

Launch a development environment :
 - cd disquaire
 - virtualenv env -p python3
 - . env/bin/activate

Launch Django server. (Go to disquaire/disquaire_project) :
 - ./manage.py runserver

If Django notifies us to migrate :
 - ./manage.py migrate

Show migrations :
 - ./manage.py showmigrations

Lorsque les modèles sont modifiés => migration automatique :
 - ./manage.py makemigrations