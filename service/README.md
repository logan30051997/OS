# Cài đặt Repositories và Repo service liên quan

**Cài đặt Yum-ultils**

```yum install yum-utils```

```yum-config-manager --add-repo "link repo"```

## Repo

**Link repo**
- [Inet repo](http://mirrors.inet.vn/centos/)
- [IDC repo](http://centos-hcm.viettelidc.com.vn/)
- [Remi repo](http://mirrors.mediatemple.net/remi/enterprise/7/remi/x86_64/)

Ví dụ: 

```yum-config-manager --add-repo "http://mirrors.inet.vn/centos/7/updates/x86_64/"```

*Lưu ý: Chọn version phù hợp và / cần*

## Service

### Database Server

1. [Mongo DB](https://repo.mongodb.org/yum/redhat/7/mongodb-org/3.3/x86_64/)
2. [MySQL 5.7](https://repo.mysql.com/yum/mysql-5.7-community/el/7/x86_64/)
3. [MySQL Connectors](https://repo.mysql.com/yum/mysql-connectors-community/el/7/x86_64/)
4. [MySQL all](https://dev.mysql.com/downloads/)
5. [PostgreSQL 10](https://download.postgresql.org/pub/repos/yum/10/redhat/rhel-7-x86_64)
6. [MariaDB Server](https://mariadb.org/download/#mariadb-repositories)

### Web Server
1. [Nginx](http://nginx.org/packages/centos/7/x86_64/)
2. [Apache](https://mirror.downloadvn.com/apache/httpd/)

### Web Service

1. [Wordpress](https://wordpress.org/download/#download-install)
2. [Drupal](https://www.drupal.org/download)
3. [Nodejs](https://rpm.nodesource.com)

### Others

1. [Php-fpm](http://rpms.remirepo.net/enterprise/)
2. [Rsyslog](http://rpms.adiscon.com/v8-stable/epel-7/x86_64/)
3. [VirtualBox](http://download.virtualbox.org/virtualbox/rpm/rhel/7/x86_64/)

Ví dụ: 

```yum-config-manager --add-repo "http://nginx.org/packages/centos/7/x86_64/"```


