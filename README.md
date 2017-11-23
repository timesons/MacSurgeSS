###surge配置shandowsocks(ss)
```
[Proxy]
随便起个名字 = custom,ip,port,AES-256-CFB,password,https://github.com/weixiubin/ss/blob/master/SSEncrypt.module

[Proxy Group]
Proxy = select,随便起个名字
Apple = select,DIRECT,Proxy
```


<mark>特别注意这里
`随便起个名字 = custom,ip,port,AES-256-CFB,password,https://github.com/weixiubin/ss/blob/master/SSEncrypt.module
`
不要有空格，我试过有空格代理不成功的情况，删除空格就可以了。</mark>
