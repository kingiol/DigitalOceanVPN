AutoInstallVPN
===============

Turn the droplet on DigitalOcean or Linode into a VPN server

## How to use:

1. Create a VPS on [DigitalOcean](https://www.digitalocean.com/?refcode=ca6e33dd0964) or [Linode](https://www.linode.com/?r=218734ebc6cd68f661f596d887a106fa038e0b86)
2. Select "Ubuntu 10.04 x64" in distributions
3. [optional] Add SSH Keys when creating the droplet
4. login to VPS
5. run bellow script
```
# download scirpt
wget https://github.com/hunterzhang86/DigitalOceanVPN/archive/master.zip
# Extract the compressed file
unzip master.zip
cd DigitalOceanVPN
# run the script
sh ./autoInstallVPN.sh
```

===================

# 对于中国用户

此脚本用于在[DigitalOcean](https://www.digitalocean.com/?refcode=ca6e33dd0964)或者[Linode](https://www.linode.com/?r=218734ebc6cd68f661f596d887a106fa038e0b86)的服务器上自动创建VPN服务从而实现自动翻墙。

DigitalOcean的最低服务器费用为$5/月 ，而Linode的最低服务器费用为$10/月。

## 使用方法：

1. 在[DigitalOcean](https://www.digitalocean.com/?refcode=ca6e33dd0964)上注册（自动获得10美元）并且创建一个Droplet(服务器) 
2. 选择镜像系统为"Ubuntu 10.04 x64"
3. [推荐，但不必须] 在创建Droplet时添加SSH Keys
4. 登录VPS
5. 依次执行以下脚本
```
# 下载脚本
wget https://github.com/hunterzhang86/DigitalOceanVPN/archive/master.zip
# 解压压缩文件
unzip master.zip
cd DigitalOceanVPN
# 执行autoInstallVPN.sh
sh ./autoInstallVPN.sh
```