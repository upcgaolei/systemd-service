# systemd-service
some systemd-service about middleware, for example, zookeeper, redis, nginx...

```
location: /etc/systemd/system/zookeeper.service
systemctl daemon-reload 重新加载配置
systemctl start zookeeper.service
systemctl stop zookeeper.service
systemctl status zookeeper.service
systemctl enable zookeeper.service 开机自启动
systemctl disable zookeeper.service 关闭自启动
```