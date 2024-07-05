# Elastic Search

端口
------
<pre>
Http：9200
Tcp：9300
</pre>

安装成功？
------
<pre>
http://localhost:9200/?pretty
</pre>

目录无权限？
------
<pre>
chown 1000:1000 logs
chown 1000:1000 data
</pre>

启动失败？
------
<pre>
sudo sysctl -w vm.max_map_count=655360
</pre>

进容器
------
<pre>
docker-compose exec elasticsearch bash
</pre>

Elastic Search Head
------
<pre>
http://localhost:9100

连接地址：http://localhost:9200/
注：启动后，等待片刻才能连上

空查询结果
cd _site
vim vendor.js
application/x-www-form-urlencoded 改成 application/json;charset=UTF-8
</pre>
