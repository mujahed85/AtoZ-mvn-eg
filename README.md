## Apache Maven Tutorial

Install Maven:-
---------------
sudo su 
apt update
apt install unzip
apt install wget
apt install default-jdk -y

Setting Path in Ubuntu16.04/18.04:-
-----------------------------------
nano /home/ubuntu/.bashrc
##Start: Java,Tomcat Path Settings
export JAVA_HOME=/usr/lib/jvm/java-1.11.0-openjdk-amd64
export MAVEN_PATH=/usr/share/maven
export CATALINA_HOME=/usr/share/tomcat7
export CATALINA_BASE=/var/lib/tomcat7
export PATH=${PATH}:${JAVA_HOME}/bin
##End: Java,Tomcat Path Settings

source /home/ubuntu/.bashrc

apt install maven -y

apt install tomcat7 -y
apt-get install tomcat7-admin
