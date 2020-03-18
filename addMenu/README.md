# 添加菜单

进入应用系统之后，在页面的最左边的菜单栏，可以看见一个添加菜单的按钮，点击按钮之后设置好此菜单的名称，点击确定，即可看见菜单栏多出来您刚刚新添加的菜单。

![](http://193.112.34.232:91/assets/img/intro/intro-1.gif)


<script type="text/javascript">
window.addEventListener("load", function() {
  var click_handle = function() {
    if (this.href.substr(-5) == ".html") {
      location.href = this.href;
    } else {
      location.href = "./index.html";
    }
  };
  var as = document.querySelectorAll(".chapter a, .navigation-prev, .navigation-next");
  for (var i = 0; i < as.length; i++) {
    as[i].addEventListener("click", click_handle, true);
    as[i].title = as[i].innerText;
  }
});
</script>