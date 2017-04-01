#  趣快出行后台部署文档

##  系统要求
1. 目前仅支持Linux
2. Go语言环境
  
##  安装部署
1. 执行以下命令下载trakelchain：  
`git clone https://github.com/trakel-project/trakelchain.git`

2. 执行以下命令运行四个节点的Trakelchain：  
`./start.sh`

3. 如果想手动起四个节点并监控状态，打开四个终端窗口，分别运行：  
```
./trakelchain -o 1 -l 8001 -t 8081 //run this on first node
./trakelchain -o 2 -l 8002 -t 8082 //run this on second node
./trakelchain -o 3 -l 8003 -t 8083 //run this on third node
./trakelchain -o 4 -l 8004 -t 8084 //run this on fourth node
```
