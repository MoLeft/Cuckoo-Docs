# 百度统计

使用方法如下：

1. 前往“百度统计”注册账号，新增网站

2. 在“代码获取”获取到下面展示的新版统计代码

```
<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?xxxxxxxxxxxxxxxxxxx";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>
```

3. 将上面代码中的“xxxxxxxxxxxxxxxxxxx”复制粘贴到主题设置中的“百度统计代码”并保存

4. 回到“百度统计”，进入“代码安装检查”检验是否生效即可（可能会有延迟，若提示没有生效请重试）