## Mac安装nvm
### 有科学上网 
 #### curl: (35) LibreSSL SSL_connect: Connection reset by peer in connection to raw.githubusercontent.com:443 
 #### curl: (7) ~~~
 ##### 网络问题  具体原因不详 
### 解决方案  ：使用终端代理
  curl cip.cc     测试自己端口  ip
  

## 修改本次终端下的代理端口  一次性使用  
### export https_proxy=http://127.0.0.1:4780 
### export http_proxy=http://127.0.0.1:4780 

#### 测试过端口改变之后 进行下边步骤

## 安装nvm 
### curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash 

##### 安装成功之后 复制以下代码

···
    export NVM_DIR="$HOME/.nvm"
   [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
 ···
## 终端 新建.bash_profile   新建文件用然后用vs code 打开  
###  code ~/.bash_profile   
### 粘贴代码。保存。 

## 刷新文件环境 sourcee ~/.bash_profile 

## 最有因为m1 Mac 终端默认的是zsh。 所以还有一步 具体原因参考nvm的GitHub。没有这一步会导致 重新打开终端就找不到nvm命令 

## touch ~/.zshrc    open ~/.zshrc   粘贴上边复制的代码  保存  。

## end～～～
# 使用 nvm install --lts 下载node


