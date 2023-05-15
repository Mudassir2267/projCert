FROM tomcat
COPY . /var/lib/jenkins/workspace/Build-PHP/my-app
WORKDIR /var/lib/jenkins/workspace/Build-PHP/my-app
EXPOSE 8080
CMD /usr/local/tomcat/bin/catalina.sh run
