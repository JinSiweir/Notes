## 安装
 brew install nginx
## 操作 
``` 
sudo nginx                 /启动nginx
sudo nginx -s quit         /快速停止nginx
nginx -V                   /查看版本，以及配置文件地址
nginx -v                   /查看版本
sudo nginx -s reload|reopen|stop|quit   /重新加载配置|重启|快速停止|安全关闭nginx
nginx -h                   /帮助
```

## 使用homebrew启动会导致权限可能不够 有些页面请求会被拦截500 
