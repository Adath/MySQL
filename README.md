<h2 align="center">MySQL</h2>

<p align="center">Repository containing the queries developed in MySQL</p>

<h6 align="center">Windows</h6>

```sql
    mysqlsh --user root --host localhost --port 3306 -p
```

```sql
    \sql
```

<h6 align="center">Manjaro</h6>

```bash
    sudo pacman -S mysql
```

```bash
    sudo mysql_install_db --user=mysql --basedir=/usr --datadir=/var/lib/mysql
```

```bash
    sudo pacman -S libsecret

    sudo pacman -S gnome-keyring

    sudo pacman -S mysql-workbench
```

```bash
    mysql -u root -h localhost -p

    use mysql

    ALTER USER 'root'@'localhost' IDENTIFIED BY 'my_password';

    exit

    sudo systemctl start mariadb

    sudo mysql_secure_installation

    sudo systemctl status mariadb

    sudo mysql -u root -p

    sudo mysql -u root -h localhost -p

    sudo mysql --user root --host localhost -p
```