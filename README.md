<p align="center"><img src="mysql.svg" width="400"></p>

<p align="center">Repository containing the queries developed in <a href="https://www.mysql.com/">👉 MySQL 👈</a></p>

<p align="center">
    <a href="https://opensource.org/licenses/MIT">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/languages/count/Adath/MySQL">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/last-commit/Adath/MySQL">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/followers/Adath?style=social">
    </a>
</p>

<h2 align="center">Connection</h2>

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

    USE mysql

    ALTER USER 'root'@'localhost' IDENTIFIED BY 'my_password';

    exit
```

```bash
    sudo systemctl start mariadb
```

```bash
    sudo mysql_secure_installation

    sudo systemctl status mariadb

    sudo mysql -u root -p

    sudo mysql -u root -h localhost -p

    sudo mysql --user root --host localhost -p
```

<h6 align="center">SHOW DATABASES</h6>

```sql
    SHOW DATABASES;
```

<h6 align="center">CREATE DATABASE</h6>

```sql
    CREATE DATABASE mysql_db;
```

<h6 align="center">USE DATABASE</h6>

```sql
    USE mysql_db;
```

<h6 align="center">SHOW TABLES AND VIEWS</h6>

```sql
    SHOW TABLES;
```