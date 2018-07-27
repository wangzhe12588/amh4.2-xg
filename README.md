# amh4.2-xg

转载备份,amh4.2西瓜哥基于vpskk修改版

## 安装

```shell
screen -S amh

wget https://raw.githubusercontent.com/wangzhe12588/amh4.2-xg/master/amh4.2.sh 

bash amh4.2.sh 2>&1 | tee amh.log

```

## 面板特点

1.支持多数据库选择,mysql5.5,mysql5.6,mysql5.7以及mariadb10.1，mariadb5.5

2.支持nginx和tengine选择，而且都开启http2

3.多版本php共存, php5.3,php5.4,php5.5以及php5.6和php7.1

4.面板默认使用php5.6

5.优化4.2面板中，ssh添加ftp账户，造成的mysql.sock权限丢失问题，导致出现面板连接数据库错误

6.添加主机时候，可以输入网站根目录，方便网一些框架如 thinkphp,laravel,zend framework，需要绑定到public目录

7.添加一些常用模块，memchache和radius，支持php7.0

8.更多功能等你发现

注：mysql 5.7 内存+swap少于1.5G就不要选择了，安装不了，编译会出错。

## 截图

![](http://ww4.sinaimg.cn/large/7de3675bgw1f71gqh87bnj20zk0hqq7f.jpg)
![](http://ww4.sinaimg.cn/large/7de3675bgw1f71gle58s8j20ur0i8td0.jpg)
![](http://ww1.sinaimg.cn/large/7de3675bgw1f71glybd19j20ov0ifdlw.jpg)

