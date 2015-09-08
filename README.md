# Abstract



---

# Update

## 2015/05/25

* Fix bug of footer jumping
* Add response interactive of demo page

---


### static view



## Attention

When you fork the theme ,you should:
delete statistics code in _includes/head.html.

like this:

```javascript
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "//hm.baidu.com/hm.js?**************************";
  var s = document.getElementsByTagName("script")[0]; :
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





