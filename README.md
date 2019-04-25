# OpenSSH 8.0p2

openssh8.0版本虽然修复了35年的bug但是源生的openssh取消了tcpwrappers的功能。导致服务器出现大量的密码扫描的问题，经过修改增加了tcpwrapper的支持。

编译过程中需要增加--with-tcp-wrappers参数。

同时打包了在centos7.5版本上的rpm包。



