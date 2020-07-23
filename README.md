

# 源地址

## 下载脚本
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
## 下载脚本
wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh

# shadowsocks

## 添加至 /etc/init.d/
chmod 777 shadowsocks

mv shadowsocks /etc/init.d/shadowsocks

## 添加执行权限
chmod 777 shadowsocks.sh
## 执行脚本安装
./shadowsocks.sh

# bbr
## 添加执行权限
chmod 777 bbr.sh
## 执行脚本安装
./bbr.sh

