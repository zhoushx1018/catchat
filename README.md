
# CatChat

《[Flask Web 开发实战](http://helloflask.com/book)》 第11章聊天室

Demo: http://CatChat.helloflask.com

![Screenshot](http://helloflask.com/screenshots/CatChat.png)



## 安装

git clone源码
```
$ git clone https://github.com/greyli/CatChat.git
$ cd CatChat
```

## 安装依赖
当前`CatChat`的实践仅支持python2

flask版本查看，如果依赖的是python3，则需要重新安装
```
$ flask --version
Python 3.5.2
Flask 1.1.2
Werkzeug 1.0.1
```

重新安装flask，通过pip(python2)安装
```
$ pip install -r requirements.txt
```

查看flask版本，是否依赖于pyton2
```
$ flask --version
Flask 1.0.2
Python 2.7.12 (default, Apr 15 2020, 17:07:12) 
[GCC 5.4.0 20160609]
```

## 应用启动
初始化本地数据库

```
$ flask forge
$ flask run
```


启动http服务

```
## Running on http://0.0.0.0:8080/
$ flask run -h 0.0.0.0  -p 8080 
```

在本地尝试访问服务

```
$ curl http://localhost:8080
```

通过浏览器访问服务

```
http://IP:8080
```

Test account

```

* email: `admin@helloflask.com`
* password: `helloflask`
```

 
 
 
