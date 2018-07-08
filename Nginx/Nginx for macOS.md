#### 下载Nginx(only for windows) [传送门](http://nginx.org)


* *安装*

        $ sudo brew install nginx
* *查看Nginx版本*

        $ nginx -v
* *启动Nginx*

        $ sudo nginx
* *查看Nginx是否启动成功*

        在浏览器中访问 http://localhost:8080
        端口号是在配置文件 nginx.conf 里面配置的，默认端口是 8080 ，配置文件的位置 /usr/local/etc/nginx
* *关闭Nginx*

        $ sudo nginx -s stop
* *重新加载Nginx*

        $ sudo nginx -s reload