To start mysql, in the terminal, type in `mysql -u root`

To create a user that can be accessed via nodejs etc, run this:
```
mysql -e "ALTER USER 'user'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root_password';"
```