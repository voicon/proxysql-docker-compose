# proxysql docker-compose learning


## start proxysql server

```code
docker-compose up -d
```

## Admin connect

```code
mysql -h127.0.0.1 -P6032 -uradmin -pradmin --prompt "ProxySQL Admin>"
```

## Application connect

```code
mysql -h127.0.0.1 -P6033 -u<mysql user> -p<mysql password>
```