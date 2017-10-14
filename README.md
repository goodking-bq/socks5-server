# socks5-server

# 用asyncio实现的一个简单的socks5服务器，仅供参考

## 支持协议
- [x] TCP
- [x] UDP
	
## 支持用户名密码验证
## 支持uvloop

使用：

usage: s5n.py [-h] [-b BIND] [-u USER] [-p PASSWORD] [-v VERSION]

使用asyncio的socks5服务器

optional arguments:
  -h, --help            show this help message and exit
  -v VERSION, --version VERSION

server arguments:
  -b BIND, --bind BIND  绑定的ip
  -u USER, --user USER  认证的用户名
  -p PASSWORD, --password PASSWORD
                        认证的密码
