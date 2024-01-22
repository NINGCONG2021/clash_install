clash安装教程

1. 在当前目录输入`bash clash_install.sh ` 
2. 输入 `sudo mv ~/.app/clash/clash.desktop /usr/share/applications/`
3. 打开更多应用

![doc/1.png](doc/1.png)

4.双击打开 clash，点击 profiles 导入节点。

![doc/3.png](doc/3.png)

5.复制你购买到的订阅地址输入到输入框里，点击 Download 下载节点。

![doc/6.png](doc/6.png)

6.点击 General，打开 Mixin。

![doc/4.png](doc/4.png)

7.打开设置，找到网络接着找网络代理。

![doc/5.png](doc/5.png)

8.设置网络代理。

![doc/2.png](doc/2.png)

9.配置git

`git config --global http.proxy 'http://127.0.0.1:7890'`

`git config --global https.proxy 'https://127.0.0.1:7890'`

10.测试

`curl https://www.youtube.com/`

配置成功为快速相应
