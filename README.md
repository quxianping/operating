operating
=========

服务器运维相关
# 监控
cacti + nagios
# 带宽分流
图片读取放在低成本机房，使用nginx的x-sendfile方式，需要处理的问题的url的失效和数据同步问题
# 数据库和缓存
数据库和cache与代码的隔离部署问题
## redis
刚刚安装，需要调整参数，备份恢复还没有经历过
## mysql
是否需要开启主从
## memcached
是否需要有监控
# 推送系统
## dove
重启中的问题，部署问题
## mosquitto
部署问题
