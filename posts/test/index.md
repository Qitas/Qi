#  测试博客


<!--more-->
>**本文同步更新至 [Youtube](https://youtu.be/ZAi4a1fyBWI) 和 [BiliBili](https://www.bilibili.com/video/av84216011/)**


## 部署


跟官网宣传的一样，部署 Hugo 网站到 Netlify 非常简单，跟着导航操作即可。

经过部署后已经可以通过 Netlify 分配的域名来访问网站了

## 自定义域名

对于想对网站使用**主域名**而言，自定义域名很简单：

1. 找到 *Domain settings* 选项卡，点击进入域名设置
2. 在 *Custom domains* 一项下点击 *Add domain alias* 来添加自定义域名
3. 在弹出来的输入框输出主域名即可
4. 在域名商处添加如下的 DNS 记录，等待 DNS 刷新，看到主域名处出现 *NETLIFY DNS* 的墨绿色标志即代表成功

```
dns1.p01.nsone.net
dns2.p01.nsone.net
dns3.p01.nsone.net
dns4.p01.nsone.net
```


