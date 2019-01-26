% prepara el repositorio para su despliegue. 
release: sh -c 'python manage.py migrate'
% especifica el comando para lanzar Decide
web: gunicorn hello_django.wsgi --log-file -
