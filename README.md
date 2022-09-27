# Fiddler-
Fiddler汉化版

fiddlercertmaker

DnsJumper

Beanstalkd web

mars

LogView

ouapi

supervisord

绿色单文件封装

MySQLMonitor.jar
 
```
java -jar MySQLMonitor.jar -h 192.168.2.6 -p 3307 -user root - pass root
```

go-oss-buckup 备份或者同步 当前images目录文件到oss对象存储

```
./go-oss-buckup --ak LTAI###Kk --as Z29AI###Kj5eY --bn BucketName --ep oss-cn-shanghai.aliyuncs.com --dir images --action list
action: 
  delete  删除
  list    下载  prefix 不填写，则全部下载
  uploadFile 上传  默认上传
```

go-es-json 采集json格式文件或者管道数据进入es

```
tail -F ./demo.json | ./go-es-json -h http://127.0.0.1:9200 -i test -t type -id id -f ./json.log
tail -F ./*.json | ./go-es-json -h http://127.0.0.1:9200 -i test -t type -id id
./go-es-json -h http://127.0.0.1:92010 -i test -t type -id id -f ./json.txt
```

![image](https://user-images.githubusercontent.com/29120060/173166176-8aee5f1f-d947-4d28-8774-f2665115d435.png)
