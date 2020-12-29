<p align="center"><img src="mysql.svg" width="400"></p>

<p align="center">Repository containing the queries developed in <a href="https://www.mysql.com/">👉 MySQL 👈</a></p>

<p align="center">
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/license/Adath/MySQL">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/languages/count/Adath/MySQL">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/last-commit/Adath/MySQL">
    </a>
</p>

<h6 align="center">Introduction</h6>

<p>🌖 DDL - Data Definition Language</p>

<p>🌗 DML - Data Manipulation Language</p>

<p>🌘 DQL - Data Query Language</p>

<p>🌑 DTL - Data Transaction Language</p>

<p>🌒 DCL - Data Control Language</p>

<h2 align="center">Installation [<a href="https://dev.mysql.com/get/Downloads/MySQLInstaller/mysql-installer-community-8.0.22.0.msi">🚀 Windows</a>]</h2>

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

<h5 align="center">TABLES</h5>

<h6 align="center">Show information about a table called h6roducts</h6>

```sql
    SHOW CREATE TABLE products;
```

<h6 align="center">Inserting values in a table called products</h6>

```sql
    INSERT INTO products (
        description, brand, price
        ) VALUES ('Notebook', 'LeNovo', 1500);
```

```sql
    INSERT INTO products (
        description, brand, price
        ) VALUES ('Caneta', 'Bic', 2);
```

```sql
    INSERT INTO products (
        description, brand, price
        ) VALUES ('Fita', 'Durex', 10);
```

```sql
    INSERT INTO products (
        description, brand, price
    ) VALUES ('Massa', 'Miojo', 2);
```

```sql
    INSERT INTO products (
        description, brand, price
        ) VALUES ('Leite', 'Ninho', 12);
```

```sql
    INSERT INTO products (
        description, brand, price
        ) VALUES ('Cereal', 'Sucrilhos', 20);
```

<h6 align="center">TRUNCATE TABLE</h6>

```sql
    TRUNCATE TABLE products
```

<h4 align="center">Pager (Linux)</h4>

```sql
    pager less -S
```

<h6 align="center">YOU CAN TELL MYSQL TO USE THE LESS PAGER ITS `-S` OPTION THAT CHOPS WIDE LINES AND GIVES YOU AN OUTPUT THAT CAN SCROLL WITH THE ARROW KEYS</h6>

<h6 align="center">THIS, NEXT TIME YOU RUN A COMMAND WITH A WIDE OUTPUT, MySQL WILL LET YOU BROWSE THE OUTPUT WITH THE LESS PAGER</h6>