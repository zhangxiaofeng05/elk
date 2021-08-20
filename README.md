## elk日志处理环境搭建
 - springboot 2.5.3
 - elasticsearch 7.12.1
 - logstash 7.12.1
 
### run
#### win10
 - elasticsearch
进入elasticsearch/bin  
双击elasticsearch.bat  
 - logstash  
进入logstash/bin  
cmd执行  
```shell script
logstash.bat -f ../config/logstash.conf
```
 - kibana  
进入kibana/bin  
双击kibana.bat