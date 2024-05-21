FROM tomcat:9.0-slim

WORKDIR /usr/local/tomcat

ADD  https://github.com/mayur4279/tmp/raw/main/mysql-connector.jar lib/mysql-connector.jar
ADD  https://github.com/mayur4279/tmp/raw/main/student.war  webapps/student.war
ADD  https://github.com/mayur4279/Projects/raw/main/3-tier-project-using-kubernetes/frontend/context.xml conf/context.xml 

EXPOSE 8080

CMD ["bin/catalina.sh", "run"]
