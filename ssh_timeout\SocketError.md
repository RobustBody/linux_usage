
# Socket error Event: 32 Error: 10053.
```
UseDNS no
systemctl restart sshd
```
by https://blog.csdn.net/u010948569/article/details/83178515

# 全局变量设置ssh超时
```
vim /etc/profile
export TMOUT=1800 #设置闲置时间为30分钟
source /etc/profile
```
# ssh客户端设置 Keep Alive
 Keep Alive\保持活动状态 设置为10秒
