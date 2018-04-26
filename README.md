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
docker ps -a
docker start ubuntu1

/var/www/html(apache2)
/var/lib/tomcat8/webapps/ROOT

http://localhost:80/

### 도커셋팅 안함 딮빡!!!!!!!!!!!!!!
- node.js 환경에서 http-server 설치후에 로컬 환경 구성
#### PATH
- 경로
- 소문자는 상대위치, 대문자는 절대위치를 나타냄
- M = moveto
- L = lineto
- H = horizontal lineto
- V = vertical lineto
- C = curveto
- S = smooth curveto
- Q = quadratic Bézier curve
- T = smooth quadratic Bézier curveto
- A = elliptical Arc
- Z = closepath


http://denvycom.com/blog/d3-js-version-4-x-examples-and-changes-from-version-3-x/
http://www.jaeminjo.com/