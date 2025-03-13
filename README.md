# BTPanel-BTKaiXin.com
## 宝塔开心版 宝塔面板开心版  官网 https://www.BTKaiXin.com
### 9.2.0，通用安装命令
```
if [ -f /usr/bin/curl ];then curl -sSO http://v920.hostcli.com/install/install_6.0.sh;else wget -O install_6.0.sh http://v920.hostcli.com/install/install_6.0.sh;fi;bash install_6.0.sh www.HostCLi.com
```

### 宝塔纯净版 9.2.0版本安装命令 [最新推荐]

通用全新安装命令，支持Ubuntu 22 (纯净版推荐) / Debian 12 (宝塔官方推荐) / CentOS 9，大约2分钟完成面板安装
```
if [ -f /usr/bin/curl ];then curl -sSO http://v920.hostcli.com/install/install_6.0.sh;else wget -O install_6.0.sh http://v920.hostcli.com/install/install_6.0.sh;fi;bash install_6.0.sh www.HostCLi.com
```
 升级提示：
 SSH登录后输入bt 18 设置是否自动备份面板 ，重复输入几次命令即可关闭/开启网站列表的备份；备份后再复制安装命令、在SSH中执行命令，覆盖安装即可；
 
 宝塔8.x版本直接覆盖安装即可升级到9.2.0版本；
 
 宝塔7.x版本，不建议覆盖安装升级到9.2.0，因为CentOS7系统也已停止维护，尽量安装Ubuntu22、Debian12、CentOS9系统。


来源： https://www.btkaixin.net/#install_linux_panel



------
------
------

# 宝塔云安全监控v2.3.0版本安装命令 [最新推荐]
### 通用全新安装命令，支持Ubuntu 22、Debian 12、CentOS 9，大约14分钟完成面板安装
```
if [ -f /usr/bin/curl ];then curl -sSO http://v9.btkaixin.net/install/btkaixin/install_btmonitor.sh;else wget -O install_btmonitor.sh http://v9.btkaixin.net/install/btkaixin/install_btmonitor.sh;fi;bash install_btmonitor.sh www.BTKaiXin.com
```

来源： https://www.btkaixin.net/#install_btmonitor 
