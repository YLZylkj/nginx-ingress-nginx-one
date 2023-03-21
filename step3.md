**安装 Nginx</br>**

1、下载 Nginx </br>

```
mkdir -p /usr/local/src
cd /usr/local/src/
wget http://nginx.org/download/nginx-1.20.2.tar.gz
```

2、解压安装包:</br>
`tar zxvf nginx-1.20.2.tar.gz`

3、进入安装包目录</br>
`cd nginx-1.20.2`

4、编译安装 </br>
`./configure --prefix=/usr/local/webserver/nginx --with-http_stub_status_module --with-http_ssl_module --with-pcre=/usr/local/src/pcre-8.35`</br>
`make `</br>
`make install`

5、查看nginx版本</br>
`/usr/local/webserver/nginx/sbin/nginx -v`