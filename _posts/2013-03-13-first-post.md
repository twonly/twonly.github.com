---
layout: post
category:  helloworld
tagline: "总有那么多个第一次"
tags: [水]
mytitle: 第一篇日志 From Github
---
{% include JB/setup %}

终于把 Jekyll+Github 搭好了，从刚接触Github，到一步步 Google +摸索，才有今天这个页面啊！终于我也可以在本地写文再 post 上去了！

前前后后，自己也弄过好几个 Blog 了，高中跟随班主任开了个网易的，大一追mm又开了个 Blogbus ，后来又弄了个免费域名和主机，吐槽/实习记录/台湾的行走游记，先后也写了100+篇，无奈免费主机向来不靠谱，说挂就挂，把日志备份到了网易后，域名也过期了，也就不再搭理了。
前段时间发现[Github Pages](http://pages.github.com) 可以做 Blog 用，折腾了快两个礼拜，才弄出个模样来。还得重新学习Jekyll倒也 ok ，毕竟Markdown语法蛮简单，而且 Liquid 跟之前用过的 Smarty 也有点类似，都是模板语言嘛。
然后就是进行改造啦！先破坏再建设，倒也不需要，自己的三角猫功夫添加些小功能，像“回到顶部”，微博按钮，已经足够了。
再有就是 Jekyll 的 post 页面 title 是根据文件命名来决定的，因此也只能用英文，这让人很不爽。(虽说这篇的名字也包含了英文，但我不用跟我不能选择还是有差别的)毕竟，每篇文章都要想一个显得 native 又 elegent 的标题哪有那么容易，加上正文用中文的话，更加不般配。研究了下代码，自己添加个 mytitle 的 metadata ，再改下 themes 里的 post.html ，我大中文标题可以显示啦！

`EOF`
