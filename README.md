# nginx-basic-auth
Starting point for experimenting from laurentbel's Gist of the same name. 

``sudo docker run -it -p 80:80 --env BASIC_USERNAME=john.doe --env BASIC_PASSWORD=myp@ssword! --env FORWARD_HOST=localhost --env FORWARD_PORT=8080 nginx-basic-auth``

Replaced in this branch with 

``sudo docker run -it -p 80:80 --env BASIC_USERNAME=john.doe --env BASIC_PASSWORD=myp@ssword! nginx-basic-auth``
