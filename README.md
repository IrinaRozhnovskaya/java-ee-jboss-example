# java-ee-jboss-example

JBOSS EAP 6.4.0

build and run 
~~~~
./mvnw clean package 
~~~~

target\java-ee-jboss-example.war >> ${JBOSS_HOME}/standalone/deployments/
~~~~
cd ${JBOSS_HOME}/bin/ standalone.bat
~~~~

 open http://localhost:8080/java-ee-jboss-example/