yum localinstall https://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm -y
yum install mysql-community-server -y 
yum --enablerepo=mysql80-community install mysql-community-server -y
systemctl start mysqld.service ## use restart after update 
systemctl enable mysqld.service
