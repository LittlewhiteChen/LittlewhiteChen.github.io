# Abstract



---

# Update

## 2015/05/25

* Fix bug of footer jumping
* Add response interactive of demo page

---


### static view

![blog sample](http://7q5cdt.com1.z0.glb.clouddn.com/blog-blog sample.png)

### active view

![blog-blogShow1](http://7q5cdt.com1.z0.glb.clouddn.com/blog-blogShow1.gif)

![blog-blogShow2](http://7q5cdt.com1.z0.glb.clouddn.com/blog-blogShow2.gif)

## Attention

When you use this theme. Please make sure to add the author's info, like this: Jekyll theme by [Gaohaoyang](https://github.com/Gaohaoyang) or Designed by [Gaohaoyang](https://github.com/Gaohaoyang) 

While you should delete statistics code in _includes/head.html.

like this:

```javascript
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "//hm.baidu.com/hm.js?**************************";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
```

And you should change the duoshuo comment code in _layouts/default.html.

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





