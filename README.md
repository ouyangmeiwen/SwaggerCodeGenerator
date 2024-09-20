# Swagger-

根据swagger 生成代理类

 

 

本机安装java环境

 

启动tomcat

Github\apache-tomcat-8.5.100-swagger\bin\startup.bat 双击运行

默认端口是8000 需要自己修改

 

打开网址

http://localhost:8000/swagger-editor-master/

 

 

打开接口地址比如：

[http://192.168.8.62:28020/swagger/index.html?urls.primaryName=%E6%89%80%E6%9C%89API](http://192.168.8.62:28020/swagger/index.html?urls.primaryName=所有API)

得到json文件

http://192.168.8.62:28020/swagger/v1/swagger.json

将内容拷贝到http://localhost:8000/swagger-editor-master/

![img](file:///C:\Users\20204\AppData\Local\Temp\msohtmlclip1\01\clip_image002.jpg)

点击生成

![img](file:///C:\Users\20204\AppData\Local\Temp\msohtmlclip1\01\clip_image004.jpg)

根据自己的需要获取 新接口的方式

![img](file:///C:\Users\20204\AppData\Local\Temp\msohtmlclip1\01\clip_image006.jpg)

拷贝这个文件到新目录里面去 注意调整命名空间以及参数。

 

注意无关的不要拷贝。底层代码不能动！