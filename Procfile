% prepara el repositorio para su despliegue. 
release: sh -c 'python manage.py migrate'
% especifica el comando para lanzar Decide
web: gunicorn web_project.wsgi --log-file -
