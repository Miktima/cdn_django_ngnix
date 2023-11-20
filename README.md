# cdn_django_nginx
## Two django projects at one nginx server
Settings for docker containers: two django projects and one nginx web server. The nginx web server container uses the latest nginx images. Settings for nginx are in nginxs.conf. This file also has links for django static files. 
There are Dockerfile to build Docker images for django projects. The file with requirements also available. The Gunicorm servers with ports 8000 and 8001 are used in the Django projects. These ports are mapped  at 4321 and 4322 nginx ports.  
