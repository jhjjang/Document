## 개발환경 구축 - with Docker

h3. Docker 설치
http://pyrasis.com/book/DockerForTheReallyImpatient/Chapter02

# local의 hosts파일의 name을 설정한다.
# docker repository의 이미지를 다운 받는다 
<pre>
docker pull jhjang/develop:0.2
</pre>
# 내려받은 이미지로 컨테이너를 생성한다. 
<pre>
docker run -i -t --name 컨테이너이름 -v 로컬소스위치:컨테이너소스위치 -p 80:80 jhjang/develop:0.2 /bin/bash
</pre>
# 컨테이너로 접속된 후 /etc/apache2/sites-enabled/000-default.conf 파일의 VirtualHost 중 ServerName(hosts파일에 설정한 Name)과 DocumentRoot를 환경에 맞게 셋팅한다.
