[![Netlify Status](https://api.netlify.com/api/v1/badges/7b1638ec-faba-4311-84cd-a6c082c4d6c7/deploy-status)](https://wiki.teamssix.com) [![GitHub stars](https://img.shields.io/github/stars/teamssix/twiki)](https://github.com/teamssix/twiki) [![](https://img.shields.io/badge/T%20Wiki%20-%E4%BA%91%E5%AE%89%E5%85%A8%E7%9F%A5%E8%AF%86%E6%96%87%E5%BA%93-blue)](https://wiki.teamssix.com/) [![](https://img.shields.io/badge/%E7%8B%BC%E7%BB%84%E5%AE%89%E5%85%A8%E5%9B%A2%E9%98%9F-%E7%9F%A5%E8%AF%86%E6%96%87%E5%BA%93-blue)](https://wiki.wgpsec.org/) [![](https://img.shields.io/badge/PeiQi-%E7%9F%A5%E8%AF%86%E6%96%87%E5%BA%93-blue)](http://wiki.peiqi.tech/) [![Twitter](https://img.shields.io/twitter/url/https/twitter.com/teamssix.svg?style=social&label=Follow%20the%20author)](https://twitter.com/teamssix) [![img](https://img.shields.io/github/followers/TeamsSix?style=social)](https://github.com/teamssix)

## 前言

`T Wiki` 是一个面向云安全方向的知识库，这一点是和其他文库最大的不同，也许这是国内第一个云安全知识文库？

搭建这个文库的起因是笔者发现在云安全方向的中文资料属实不多，少有的这些资料也很散乱，于是搭建了这个文库。

文库的地址为：[wiki.teamssix.com](https://wiki.teamssix.com/)

## 本地部署

```bash
git clone https://github.com/teamssix/TWiki.git --depth 1
cd TWiki
npm install --global yarn
yarn install
yarn docs:build
```

build 完之后，将 docs/.vuepress/dist 目录下的文件复制到你的 nginx 或者 apache 服务的网站根目录下即可。

> 注意：node 版本需要大于或等于 12

## 文库介绍

首先来看文库首页，文库主要分成了三个板块，分别为`云服务`、`云原生`、`云安全资源`

![](https://cdn.jsdelivr.net/gh/teamssix/BlogImages/imgs/202204152146075.png)

首先来看`云安全资源`板块，这个板块是我个人觉着整个知识库较为与众不同的地方，在这里可以看到汇总的云安全资源，比如云安全相关的文章、公众号、工具、靶场等等。

![](https://cdn.jsdelivr.net/gh/teamssix/BlogImages/imgs/202204152146469.png)

这部分的内容我也同步到了 Github 上单独作为一个项目，项目名称叫做 awesome-cloud-security，项目地址为：[https://github.com/teamssix/awesome-cloud-security](https://github.com/teamssix/awesome-cloud-security)

如果你知道一些比较好的云安全资源，欢迎留言补充，我会更新到这个板块中，首页的贡献者处也将出现你的身影。

在`云服务`板块可以看到云服务方向的文章、笔记

![](https://cdn.jsdelivr.net/gh/teamssix/BlogImages/imgs/202204152147429.png)

在`云原生`板块可以看到云原生方向的文章、笔记

![](https://cdn.jsdelivr.net/gh/teamssix/BlogImages/imgs/202204152147002.png)

目前文库的东西不算多，不过未来会不断更新，如果想要投稿，那么在`关于文库`中可以找到投稿的方式。

## 最后

相信通过这些资料能够在一定程度上帮助想要学习或者正在学习云安全的人，同时也欢迎读者一起来完善这个文库，从而帮助到更多的人，一起助力国内云安全的发展。

>  更多信息欢迎关注我的个人微信公众号：TeamsSix

<div align=center><img width="800" src="https://cdn.jsdelivr.net/gh/teamssix/BlogImages/imgs/202204152148071.png" div align=center/></div>