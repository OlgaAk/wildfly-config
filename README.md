# wildfly-config
server config for jsm project

files in deployment folder:
* activemq-ra2.rar	// jms adapter, see config in standalone-full.xml		
* postgresql-42.2.20.jre6.jar // db adapter see config in standalone-full.xml
* javaee-1.0.war // java web app

run command 
./standalone.sh -c standalone-full.xml    

activemq
command ./activemq start
admin http://127.0.0.1:8161/index.html


