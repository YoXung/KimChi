#### 下载安装Tomcat 9.0 [传送门](https://tomcat.apache.org/download-90.cgi)
* *解压到指定目录下*
  ```
  解压到：/Users/用户名/
  （当下最新版本为Apache Tomcat 9.0.39）
  ```
* *配置Tomcat环境变量*
  ```
  $ vi ~/.bash_profile
        
  # Setting PATH for Apache Tomcat 9.0.39
  PATH=$PATH:/Users/用户名/apache-tomcat-9.0.39/bin
        
  :wq
  ```
* *生效环境变量*
  ```
  $ source ~/.bash_profile
  ```
* *对Tomcat目录进行权限操作*
  ```
  $ sudo chmod 755 /Users/用户名/apache-tomcat-9.0.39/bin/*.sh
  ```
* *启动Tomcat*
  ```
  $ cd /Users/用户名/apache-tomcat-9.0.39/bin
  $ sudo sh startup.sh
  ```
* *停止Tomcat*
  ```
  $ sudo sh shutdown.sh
  ```
