## Abstract

这是我个人的前端开发学习站点，如果你喜欢我的站点，可以相互交流学习。[主页](http://littlewhitechen.github.io/)



## Update

Time       | Content(更新功能模块的介绍)
:----------------------------------------: | :----------------------:
2015-09-22 | 优化了移动端，比较喜欢QQ空间的样式，就优化了一下移动端，看起来会更舒适！
2015-09-18 | 增加了Site板块，用来展示项目。以后做的项目基本都会陆续上传到站点上。
2015-09-14 | 发表了在线简历第一版，博客坚持总结自己所学的知识！
2015-09-09 | 添加了多说评论的第三方系统，有访问我网站的朋友可以评论我的文章，同时后期想增加留言板功能。欢迎有好点子的朋友推荐一些新技术，非常感谢啦！
2015-09-08 | 1、初始建站，主页增加了四个模块，分别为 Home Site About Resume功能模块。<br />2、其中Site分页主要是后期用于前端资源收集和项目展示。





### Static view

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










