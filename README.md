myBlog
======

blog code, python/flask


个人博客。

Download

$ git clone https://github.com/ustcdane/myBlog

Quick Start

配置数据库连接参数：config.py 创建table

$ python data.py

运行 app

$ python myapp.py

通过Admin 管理数据

http://localhost:5555/blog/admin/ 注意根据需要修改访问权限。

我在自己的机器上用nginx搭建的，具体可以参考我的博客中的方法。

sudo service nginx restart sudo uwsgi -x uwsgi_config.xml --daemonize /tmp/uwsgi.err.log
