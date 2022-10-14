redis 在   usr/local/redis 

# 下载
wget http://download.redis.io/releases/redis-5.0.7.tar.gz
# 解压
tar -zvxf redis-5.0.7.tar.gz  解压


mv /root/redis-5.0.7 /usr/local/redis

在redis 下
./bin/redis-server& ./redis.conf