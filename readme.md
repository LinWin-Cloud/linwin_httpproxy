## linwin_httpproxy 反向代理服务器软件
基于LinWinCloud开发的编程语言 KyLin所开发.

- 基于KyLin编程语言开发
- 适用于Windows,Mac,Linux,在类Unix系统上KyLin运行最好

### 安装KyLin编程语言
从这下载对应版本: https://gitee.com/LinWin-Cloud/kylin-language/releases
按照教程安装即可，以下默认以Linux版本下安装完成为实例

### 运行
> kylin main_http_proxy.ky

### 配置
编辑 config.ky，修改以下两行代码即可
- proxy_url: 需要反向代理的链接
- start_port: 在本地端口上开启的端口
```
var proxy_url = "https://www.bing.com/"
var start_port = 8080
```

### 使用用途
- 作为反向代理服务器，可以影藏服务器的真实IP
- 镜像网站
- 利用云服务器等，可以反向代理国外网站，国内就可以访问了.

### 联系
如果对初中生自制的KyLin编程语言等的感兴趣请联系
- QQ: 2382546858
