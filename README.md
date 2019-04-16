# static
放一些需要https引入到别的网站用的js内容。 主要是小书签。

## 网易云翻译2.0
https://fanyi.youdao.com/web2/  

这东西特别好用， 不过现在多年不维护。小书签里 http内容加载到https会挂。在这里做了个镜像，修改链接到https

<a href='javascript: void((function() %7Bvar element %3D document.createElement(%27script%27)%3Belement.id %3D %27outfox_seed_js%27%3Belement.charset %3D %27utf-8%27,element.setAttribute(%27src%27, %27https://cdn.jsdelivr.net/gh/lemon-machine/static@master/seed.gh.js%3F%27 %2B Date.parse(new Date()))%3Bdocument.body.appendChild(element)%3B%7D)())'>https修复版本的网易云翻译</a>
















=============分割线=============
下面是修理的log

gist 不行

repo 也不行

有人出 http://cdn.jsdelivr.net/gh

jsdelivr 有一个 cdn

还有人说 gitraw域名是可以的。待我试一试

https://cdn.jsdelivr.net/gh/lemon-machine/static/master/test.js?1555395260000   这个链接不行


rawgit 倒闭了

```
<script>
    var sScriptURL ='<script-URL-here>'; 
    var oReq = new XMLHttpRequest(); 
    oReq.addEventListener("load", 
       function fLoad() {eval(this.responseText + '\r\n//# sourceURL=' + sScriptURL)}); 
    oReq.open("GET", sScriptURL); oReq.send(); false;
</script>
```

有人提出可以走eval


https://cdn.jsdelivr.net/gh/lemon-machine/static/

原来分支会变成@master类似版本号一样的东西

https://cdn.jsdelivr.net/gh/lemon-machine/static@master/test.js

真正地址是这样



