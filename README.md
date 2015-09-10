## Abstract

这是我个人的前端开发学习站点，如果你喜欢我的站点，可以相互交流学习。[主页](http://littlewhitechen.github.io/)

---

## Update

Time       | Content(更新功能模块的介绍)
:----------------------------------------: | :----------------------:
2015-09-8       | 1、初始建站，主页增加了四个模块，分别为 Home Site About Resume功能模块。<br />2、其中Site分页主要是后期用于前端资源收集和项目展示。
2015-09-9       | 添加了多说评论的第三方系统，有访问我网站的朋友可以评论我的文章，同时后期想增加留言板功能。欢迎有好点子的朋友推荐一些新技术，非常感谢啦！


---


### static view

* 主页
 
![Home](http://littlewhitechen.github.io/img/blog/Home.PNG)

* 手机版

![Mobile](http://littlewhitechen.github.io/img/blog/mobile.PNG)



## Attention

* 如果fork我的主题的话，需要首先配置自己的身份信息，在`_config.yml`文件中修改自己的信息。


* 当然你也想使用多说第三方评论，你可以注册一个多说的域名，配置好你自己的多说`js`脚本
  **在`_layouts/default.html`文件中操作.**

like this:

```javascript
var duoshuoQuery = {short_name:"******"};
    (function() {
        var ds = document.createElement('script');
        ds.type = 'text/javascript';ds.async = true;
        ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
        ds.charset = 'UTF-8';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(ds);
})(); 
``` 










