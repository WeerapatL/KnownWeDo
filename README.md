# KownWeDo
INT206 Software Process Management Project     
Link วิดิโอการทำงานของระบบ : https://www.youtube.com/watch?v=sY4eLuRwZ6s

# Getting started
Clone git into your device </br>
command : "git clone https://github.com/surakiti/KnownWeDo.git"  


### 1. Apache Maven 
install "Apache Maven" </br>
Download : http://maven.apache.org/download.cgi </br>
$ cd 'your directory that clone git' </br>
$ mvn clean install </br>
you can use maven with IDE to config dependencies in 'POM.xml' file </br>
example 'POM.xml' file https://github.com/surakiti/KnownWeDo/blob/master/KnowWeDo/pom.xml


### 2. Apache Tomcat
install "Apache Tomcat" </br>
Download : https://tomcat.apache.org/download-80.cgi   </br>
install server on NetbeansIDE </br>
choose 'Apache Tomcat Server' and you set your username and password


### 3. MySQL Community Server 5.7 
install Database Server : 'MySQL Community Server 5.7'</br>
* [Windows]  
Download : https://dev.mysql.com/downloads/windows/installer/5.7.html  

* [MacOS]  
Download : https://dev.mysql.com/downloads/mysql/ </br>
(select platform 'MacOSX' and dowload dmg file)</br>
edit file command : </br>
.bash_profile</br>
#Add MySQL </br>
export MYSQL_ROOT=/usr/local/mysql </br>
export PATH=$MYSQL_ROOT/bin:$PATH</br>
open terminal command : </br>
mysql -u root -p</br>
you enter password that you got at installing</br>
*you can set new password command :</br>
" SET PASSWORD = PASSWORD('your password'); "</br>

you can use MySQL Workdbench for managing database.

# Config Properties
create file config.properties in '/src/main/resoures' and you initial </br>
dburl=${databaseURL}</br>
dbuser=${databaseUsername}</br>
dbpassword= ${databasePassword}</br>

# Members
5810500070 วีระภัทร ลออทรัพยาภัทร

58130500081 สุรกิติ โสภณธนพัต

58130500093 เอกราช อัศวรักษ์สกุล

58130500095 จิรายุ จันทร์พงษ์

58130500101 สมัชญ์ศักย์ ภาคธูป

58130500108 ฉันทวัฒน์ ประดิษฐ
