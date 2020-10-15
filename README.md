# xie

>这是一个简单的全栈web App,基于 Deno + Vue + Mysql
##Clinet

>运行在Brower(浏览器)里的应用程序Code（html + js + css）

##Server

>运行在Linux上的Web服务器

功能：

-响应浏览器HTTP请求

```sh
#安装unzip解压工具
sudo apt install unzip

curl -fsSL https://deno.land/x/install/install.sh | sh 


#拷贝二进制文件
sudo cp .deno/bin/deno /usr/bin

#检查是否安装成功
deno --version

#克隆仓库
git clone https://github.com/xieguozhen/xie.git

cd文件夹
vim mod.js
deno run --allow-net mod.js

curl localhost:8080
```

##Datebase

 持久化数据，保存Browser浏览器端用户需要的数据
