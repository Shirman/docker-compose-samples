### mysql初始化示例
本示例使用了mariadb,mariadb是mysql的一个分支,更多信息请访问[官网](https://mariadb.org/)

### 文件结构
```
mysql_init
|-- sql 数据库初始化sql脚本
|-- docker-compose.yml
|-- init-db.sh shell脚本，执行sql
|-- README.md
```
#### 启动mysql
`docker-compose up -d`

#### sql初始化
`docker-compose up mysql-init`