# webrtc-https-call
可在Electron和浏览器中进行视频通话（含客户端和服务器端）
# 使用环境
安装配置Electron、Nodejs和VSCode；  
使用npm install安装依赖包；  
在launch.json中配置runtimeExecutable成npm安装路径；  
在终端运行node server.js；  
在浏览器地址栏中输入http://localhost:18080或者https://服务器ip:18081；  
在浏览器中打开另外一个新的窗口在地址栏中输入http://localhost:18080或者https://服务器ip:18081；  
服务器ip也就是开启server服务的电脑的ip；  
在使用https时，需要配置证书，也可以是自签名证书；  
登录名称可输入任意字符，没有做限制；  
除使用浏览器，还可使用Electron，在同一电脑上两个Electron窗口会出现摄像头占用问题
