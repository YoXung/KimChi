#### 下载安装Maven [传送门](http://maven.apache.org/install.html)

##### Maven中心存储库 [传送门](http://search.maven.org)

* *解压到指定目录下*

        解压到：/Users/用户名/
        （当下最新版本为apache-maven-3.6.1）
* *配置Maven环境变量*

        $ vi ~/.bash_profile
        
        export M2_HOME=/Users/用户名/apache-maven-3.6.1
        export PATH=$PATH:$M2_HOME/bin
        :wq
* *生效*

        $ source ~/.bash_profile
* *查看是否安装成功*

        $ mvn -v
