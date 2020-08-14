# github-clear
利用selenium+chromedriver 清空指定github账户下所有的项目仓库

## 功能介绍

1. 通过用户名和密码登录github
2. 获取仓库列表
3. 循环删除仓库

> chrome和chromedriver版本需要对应  
> chrome和chromedriver版本需要对应  
> chrome和chromedriver版本需要对应  
> 重要的事情说三遍......

## 用法
1.1. 帮助说明
* 显示帮助信息： `go run github-clear.go` 
```shell
Usage of main_go:
  -d string
        chromedriver绝对路径 (default "./drivers/chromedriver")
  -p string
        github登录密码
  -s int
        chromedriver server端口 (default 9515)
  -u string
        github登录用户名
```

1.2 开始运行
运行命令： `go run github-clear.go -u=uname -p=pwd`

## 下载

已经编译好的平台有： [点击下载](https://github.com/llychao/github-clear/releases)

- windows/amd64
- linux/amd64
- darwin/amd64

#### 3. 附录：
> chromedriver之 与 chrome 版本映射表及其下载地址:
https://blog.csdn.net/huilan_same/article/details/51896672



