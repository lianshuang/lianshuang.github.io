# lianshuang.github.io
<a href="http://lianshuang.github.io" target="_blank">查看在线demo</a>

[http://lianshuang.github.io](url?_blank)

var aTagArr = [].slice.apply(document.getElementsByTagName("a"));

aTagArr.forEach(function (e, i) {
  e.href.indexOf("_blank") > -1 ? e.target = "_blank" : null;
})
