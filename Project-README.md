# Project-5 IMPLEMENT A CLIENT SERVER ARCHITECTURE USING MYSQL DATABASE MANAGEMENT SYSTEM

### Setup Linux-based EC2 virtual servers

![my sql servers on AWS](/images/mysqlservers.jpg)

#### update both linux servers

`sudo apt update`

`sudo apt upgrade`

### install mysql server on the server

`sudo apt install mysql-server`

#### confirm mysql-server service is started

![my sqlserver service](/images/mysqlserver%20service.jpg)

### reset mysql root password

`Alter user root@localhost identified with mysql_native_password by 'Welcome123';`

`sudo mysql_secure_installation`

### install mysql client

`sudo apt install mysql-client`
![my sql client](/images/mysql-client.jpg)

### connect to the database from the client

`sudo mysql -h 172.31.32.95 -u sql_client -p`
![connecting to sqlserver from sqlclient](/images/connect-from-client.jpg)
