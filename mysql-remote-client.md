Halo teman-teman semuanya, pada kesempatan kali ini kita semua akan belajar bagaimana cara Mysql Remote Client,

<h3>Mengatur Mysql</h3>

```sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf```

Ubah bind-address  menjadi 0.0.0.0

<h3>Restart Mysql</h3>

```sudo systemctl restart mysql```

<h3>Masuk  Mysql</h3>

```sudo mysql```

Jika ada password 

```mysql -u root -p```

<h3>Tambah User Mysql</h3>

```CREATE USER 'izaldev'@'%' IDENTIFIED WITH mysql_native_password BY 'passwordkamu';```

<h3>Edit User Mysql</h3>

```ALTER USER 'izaldev'@'%' IDENTIFIED WITH mysql_native_password BY 'passwordkamu';```

<h3>Permission User Mysql</h3>

```GRANT CREATE, ALTER, DROP, INSERT, UPDATE, DELETE, SELECT, REFERENCES, RELOAD on *.* TO 'izaldev'@'%' WITH GRANT OPTION;```

```FLUSH PRIVILEGES;```

<h3>Exit Mysql</h3>

```exit```

<h3>Allow Port Mysql 3306</h3>

```sudo ufw allow 3306```




