TOMCAT
=========

通过 ansible 部署 tomcat 服务

Installation
------------

`ansible-galaxy install gengxiankun.tomcat`

Role Variables
--------------

variable | description
------------ | -------------
OPT_PATH | 部署目录
SERVER_NAME | 服务名称
TOMCAT_FIST_VERSION | tomcat 主版本，比如 9.0.39 ，它的主版本就是 9
TOMCAT_VERSIION | tomcat 版本号
JAVA_OPTS | java 运行时参数
TOMCAT_PORT | tomcat 端口
TOMCAT_DOC_BASE | 代码目录

Dependencies
------------

依赖于 JAVA 环境

Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.tomcat

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
