# docker-redis
### 先執行以下shell
```
#echo never > /sys/kernel/mm/transparent_hugepage/enabled
#sysctl -w net.core.somaxconn=2048
or 
# echo "net.core.somaxconn=2048" >> /etc/sysctl.conf
```
