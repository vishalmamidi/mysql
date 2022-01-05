```
netstat -tlnp
```
```
ps -ef | grep mysql
```
```
spring.datasource.url=jdbc:mariadb://localhost:3306/jb-application
spring.datasource.username=root
spring.datasource.password=vam@123
```


```
spring.datasource.url=jdbc:mariadb://localhost:3306/jb-application
spring.datasource.username=root
spring.datasource.password=root
```

#mysql
wsl -d Debian
wsl.exe -d Ubuntu
sudo mysql # Logs in automatically into MariaDB

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'my_new_pass';
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'ROOTroot@1';
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';
FLUSH PRIVILEGES;
mysql -u root -pROOTroot@1
mysql -u root -proot

#MariaDB

```
ALTER USER 'root'@'localhost' IDENTIFIED BY 'root';
```
