# Kiểm tra thông tin cơ bản khi vào Server

## 1. Kiểm tra OS, Kernel, Arch(Architecture)


```# hostnamectl status```

*Output*

<img src=https://www.devopstechnoz.com/wp-content/uploads/2020/06/image-21.png>


## 2. Kiểm tra thông số CPU

- **Kiểm tra version**

```dmidecode -t processor | grep -i version```

- **Kiểm tra cache**

```dmidecode -t processor | grep -i cache```

- **Kiểm tra core**

```dmidecode -t processor  | grep -i count```

```lscpu```

## 3. Kiểm tra Memory

- **Kiểm tra bộ nhớ RAM và Swap**

```free -m```

- **Kiểm tra slot cắm Ram**

```dmidecode -t memory | grep -i "Number of devices"```

- **Kiểm tra slot cắm Ram**

```dmidecode -t memory | grep -i "Number of devices"```

## 4. Tiến trình đang chạy


- **Kiểm tra tiến trình**

```top htop```

```ps aux```

## 5. Các Service, Port đang mở 

- **Cổng đang mở**

```netstat -tulpn```

- **Các Service đang chạy**

```systemctl list-unit-files | grep enabled```

## 6. Kiểm tra Network, IP, Time

``` ip a```

