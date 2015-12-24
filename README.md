Flask 知识点&资源总结
===

    flask 知识点&资源总结 origin by neo1218

## Flask 知识点汇总
### 1. WSGI
#### 文章:
    1. [WSGI简介](http://segmentfault.com/a/1190000003069785)
    2. [WSGI规范笔记](http://segmentfault.com/a/1190000002717571)
##### 代码:
    1. [flask 源码中的wsgi app](https://github.com/mitsuhiko/flask/blob/master/flask%2Fapp.py#L1937)

### 2. werkzeug
#### 文档:
    1. [werkzeug 文档](http://werkzeug.pocoo.org/)
#### 代码:
    2. [werkzeug 源码](https://github.com/mitsuhiko/werkzeug)

### 3. route 装饰器
#### 文档:
    1. [Routing](http://flask.pocoo.org/docs/0.10/quickstart/#routing)
#### 文章:
    1. [这不是魔法](http://python.jobbole.com/80956/)
    2. [werkzeug的URL Routing](http://werkzeug.pocoo.org/docs/0.11/routing/)
#### 代码:
    1. [route装饰器第一次提交源码](https://github.com/mitsuhiko/flask/commit/33850c0ebd23ae615e6823993d441f46d80b1ff0#diff-ddeb74475c4912b6cc688dfc962b4b1cR226)

### 4. Jinja2
#### 文档:
    1. [Jinja2文档](http://jinja.pocoo.org/)
#### 视频:
    1. [Code Generation in Python: Dismantling Jinja](https://www.youtube.com/watch?v=-NPuhYWzi-c)
#### 代码:
    1. [Jinja2源码](https://github.com/mitsuhiko/jinja2)

### 5. request & application context
#### 文档:
    1. [The Request Context](http://flask.pocoo.org/docs/0.10/reqcontext/)
    2. [The Application Context](http://flask.pocoo.org/docs/0.10/appcontext/#the-application-context)
#### 文章:
    1. [Flask 的 Context机制](https://blog.tonyseek.com/post/the-context-mechanism-of-flask/)
    2. [werkzeug的Context Local模块](http://werkzeug.pocoo.org/docs/0.11/local/)
    3. [werkzeug的Request模块](http://werkzeug.pocoo.org/docs/0.11/wrappers/)
#### 视频:
    1. [Advanced Flask Pattern](https://www.youtube.com/watch?v=KOvgfbBFZxk)
    2. [Advanced Flask Pattern QA session](https://www.youtube.com/watch?v=XAARbHEjZUQ)

### 6. 蓝图
#### 文档:
    1. [Modular Applications with Blueprints](http://flask.pocoo.org/docs/0.10/blueprints/#my-first-blueprint)
    2. [Application Factories](http://flask.pocoo.org/docs/0.10/patterns/appfactories/)
#### 代码:
    1. [木犀官网的架构](https://github.com/Muxi-Studio/muxi_site)

### 7. 数据库的使用
#### 文档:
    1. [Using SQLite 3 with Flask](http://flask.pocoo.org/docs/0.10/patterns/sqlite3/)
#### flask扩展:
    1. [flask-sqlalchemy](https://github.com/mitsuhiko/flask-sqlalchemy)
    2. [flask-redis](https://github.com/underyx/Flask-Redis)
#### 文章:
    1. [Using Celery With Flask](http://blog.miguelgrinberg.com/post/using-celery-with-flask)
#### 代码:
    1. [sql数据库,flask原生SQL语句](http://flask.pocoo.org/docs/0.10/tutorial/schema/)
    2. [sql数据库,使用flask-sqlalchemy](https://github.com/Muxi-Studio/muxi_site/blob/master/muxiwebsite%2Fmodels.py)

### 8. rest api
#### 文章:
    1. [REST](http://searchsoa.techtarget.com/definition/REST)
    2. [Designing a RESTful API with Python and Flask](http://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)
#### 工具:
    1. [终端工具 httpie](https://github.zohttps://github.com/jkbrzt/httpieem/)
    2. RESTClient
#### 代码:
    1. [学而api](https://github.com/Muxi-Studio/xueer_be/tree/master/xueer/api_1_0)
#### 木犀的轮子:
    1. [rest](https://github.com/neo1218/rest)

### 9. 部署
#### 文章:
    1. [How To Serve Flask Applications with uWSGI and Nginx on CentOS 7](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uwsgi-and-nginx-on-centos-7)
#### 代码:
    1. [学而的uwsgi配置文件](https://github.com/Muxi-Studio/xueer_be/blob/master/xueer.ini)

### 10. 优化
#### flask扩展:
    1. [Frozen-Flask](http://pythonhosted.org/Frozen-Flask/)
    2. [flask-cache](https://pythonhosted.org/Flask-Cache/)

## flask扩展
    1. [flask扩展](http://flask.pocoo.org/extensions/)
    2. [flask扩展开发](http://docs.jinkan.org/docs/flask/extensiondev.html)
    3. [扩展导入的源码](https://github.com/mitsuhiko/flask/blob/master/flask%2Fext%2F__init__.py)

## powered by flask
flask官方纪录:
    1. [powered by flask](http://flask.pocoo.org/community/poweredby/)
其他:
    1. [来自豆瓣](http://www.douban.com/group/topic/32753119/)
    2. [学而](开发中)
    3. [木犀官网](开发中)
    4. [西窗烛](http://www.xichuangzhu.com/)
    5. [blog bar](http://www.blogbar.cc/)

## 其他
[mana: the missing startapp command for flask](https://github.com/neo1218/mana)

## Flask 大法好  Flask 大法好  Flask 大法好  Flask 大法好
