# mocodemo
###请运行以下命令运行demo:
```
命令行：
　
java -jar moco-runner-0.11.0-standalone.jar start -p 12306 -c foo.json

浏览器或postman输入：

localhost:12306/test

```
http://blog.csdn.net/vite_s/article/details/54583243

启动https服务
启动https服务，需要先生成证书，并用如下命令启动服务：地方多发呆发地方的地方的地方的发呆发：java -jar <path-to-moco-runner> https -p <monitor-port> -c < configuration -file> --https <path-to-cert.jks > --cert mocohttps --keystore mocohttps

<path-to-moco-runner>：moco-runner-0.11.0-standalone.jar包的路径
<monitor-port>：http服务监听的端口
<configuration -file>：配置文件路径
<path-to-cert.jks>：证书路径