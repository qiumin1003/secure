# /etc/hosts.allow是否添加具体可以ssh服务器的ip/ip段

- 操作方法
> Linux默认关闭该功能，如已开启，请关闭，关闭方法：
```
yum remove telnet-server 
```

- 判断依据
> 根据是否可以从远端服务器通过telnet登录到此服务器判断

- 备注
> Windows请填是