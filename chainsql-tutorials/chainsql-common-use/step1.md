快速部署4个chainsql节点

1. 执行命令 `wget http://chainsql.net/chainsql-script.tar.gz && tar zxvf chainsql-script.tar.gz && rm chainsql-script.tar.gz&& chmod +x run.sh`{{execute}} 下载脚本

2. 执行命令 `./run.sh`{{execute}} 下载chainsqld节点及4个配置文件

3. 执行命令 `cd ~/chainsql && ./startAll.sh`{{execute}} 启动4个节点

4. 执行命令 `cd ~/chainsql/1 && ./chainsqld server_info`{{execute}}可查看节点状态

5. 执行命令 `cd ~/chainsql && ./stopAll.sh`{{execute}}停止运行节点