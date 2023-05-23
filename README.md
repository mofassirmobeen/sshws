# Sshws
</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>
</div>

# Required
- DOMAIN
- DEBIAN 10 / Ubuntu 20 LTS
- CPU MIN 1 CORE
- RAM 1GB

# protokol tunneling
- Support Wildcard ✅
- SSH Websocket : 80
- SSH SSL Websocket : 443
- Stunnel4 : 222,777
- Vmess WS TLS : 443
- Vless WS TLS : 443
- Trojan WS TLS : 443
- Shadowsocks WS TLS : 443
- Vmess WS none TLS : 80
- Vless WS none TLS : 80
- Trojan WS none TLS : 80
- Shadowsocks WS none TLS : 80
- Vmess gRPC : 443
- Vless gRPC : 443
- Trojan gRPC : 443
- Shadowsocks gRPC : 443

## Update & Upgrade First Your VPS for Debian 9 STRETCH & 10 BUSTER

  ```html
  apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

  ```

## Update & Upgrade First Your VPS for Ubuntu 18 LTS & 20 LTS

  ```html
  apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot

  ```

## INSTALLATION SCRIPT

  ```
  sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/givpn/sshws/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
  ```

<p>
  
[![Telegram](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=8AF771&width=435&lines=Daftar+Ip+Kontak+Telegram+Klik+👈)](https://t.me/givpn)
</p>
  
<p>
  
[![Telegram](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FC00E1&width=435&lines=buy+me+ko-fi+Klik+👈)](https://ko-fi.com/givpn)
</p>
