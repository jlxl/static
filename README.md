# static
放一些需要https引入到别的网站用的js内容。 主要是小书签。


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



