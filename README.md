# 在 Ubuntu 18.04.6 上安装 Seafile 9.0.4 版本
鉴于使用官方脚本在 Ubuntu 18.04.6 安装失败，从原来已经安装过的服务器上将之前的安装脚本复制下来备份，未作任何修改。

在运行脚本之前需要先执行以下命令
```
apt-get install libjpeg-dev
pip3 install --upgrade pip
pip3 install --upgrade setuptools
pip3 cache purge
pip3 install Cython
```
然后运行 `bash seafile-9.0_ubuntu 9.0.4` 即可，在阿里云国内版 Ubuntu 18.04.6 系统上测试，可以安装成功，其他系统未测试。
