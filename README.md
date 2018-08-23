## NtyCo

#### coroutine
[实现原理](https://github.com/wangbojing/NtyCo/wiki/NtyCo%E7%9A%84%E5%AE%9E%E7%8E%B0)
![](http://bojing.wang/wp-content/uploads/2018/08/status_machine.png)


```
$ make
```


```
$ ./bin/nty_server
```

#### mul_process, mul_core
```
$ ./bin/nty_server_mulcore
```
#### websocket
```
$ ./bin/nty_websocket_server
```

#### bench
```
$ ./bin/nty_bench
```
![](http://bojing.wang/wp-content/uploads/2018/08/nty_bench_ntyco.png)
![](http://bojing.wang/wp-content/uploads/2018/08/nty_bench_nginx.png)


#### http server
```
$ ./bin/nty_http_server_mulcore
```

![](http://bojing.wang/wp-content/uploads/2018/08/ntyco_ab.png)![](http://bojing.wang/wp-content/uploads/2018/08/nginx_ab.png)
