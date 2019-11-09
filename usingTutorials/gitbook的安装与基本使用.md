## 1.Node.js安装

### 1.1.什么是Node.js

 Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台， 用来方便地搭建快速的， 易于扩展的网络应用 



### 1.2.Node.js的安装

[安装教程]( https://blog.gtwang.org/web-development/install-node-js-in-windows-mac-os-x-linux/ )



### 1.3.Node.js安装成功的检验

cmd下运行node -v





## 2.GitBook安装

Gitbook是从NMP安装的，命令行(打开cmd，路径每个电脑不一)：

```
C:\Users\lenovo> npm install gitbook-cli -g
```

安装完之后，你可以检验下是否安装成功：

```
C:\Users\lenovo> gitbook -V
0.3.3
```





## 3.目录初始化

在目录下输入gitbook init，可生成一系列目录文件

gitbook serve可自动生成本地预览，默认端口：4000





## 4.发布到github中



##### 1.创建仓库

##### 2.如果这个文件目录是第一次，则需要

		1. git init
  		2. git add .
  		3. git commit - m ""(注意，如果一次提交多个文件，最好不要写-m了，否则每个文件的注释都一样)
  		4. git remote add 分支名 git地址 
  		5.   git push 分支名 master   



##### 3。如果不是第一次，则需要