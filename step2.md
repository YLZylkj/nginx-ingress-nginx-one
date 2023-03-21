**安装 Pcre</br>**


1、下载 pcre </br>

`mkdir -p /usr/local/src`
`cd /usr/local/src/`
`apt  install -y wget`
 `wget http://downloads.sourceforge.net/project/pcre/pcre/8.35/pcre-8.35.tar.gz`



2、解压安装包:</br>
`tar zxvf pcre-8.35.tar.gz`

3、进入安装包目录</br>
`cd pcre-8.35`

4、编译安装 </br>
`./configure`</br>
`make && make install`

5、查看pcre版本</br>
`pcre-config --version`