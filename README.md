operating
=========
服务器运维相关

# 监控
=======================================
### cacti
### nagios

# 带宽分流
=======================================
图片读取放在低成本机房，使用nginx的x-sendfile方式，需要处理的问题的url的失效和数据同步问题

# 数据库和缓存
=======================================
数据库和cache与代码的隔离部署问题

### redis
刚刚安装，需要调整参数，备份恢复还没有经历过

### mysql
是否需要开启主从

### memcached
是否需要有监控

# 推送系统
=======================================
### dove
重启中的问题，部署问题

### mosquitto
部署问题


# 日志
=======================================
(1) dove 日志每日切分
(2) mosquitto 日志没有切分，需要使用cronolog，每日100MB
(3) nest 日志每日切分
(4) nginx 日志无切分，需要使用cronolog
