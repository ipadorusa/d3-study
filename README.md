# d3-study


## 도커 셋팅

docker pull ubuntu
docker run -it -p 80:80 -p 8080:8080 --name=ubuntu1 ubuntu
apt update
apt install nano
apt install apache2
apt install tomcat8
service apache2 start/stop/restart

docker exec -it ubuntu1 bash

/var/www/html(apache2)
/var/lib/tomcat8/webapps/ROOT

http://localhost:80/

### 도커셋팅 안함