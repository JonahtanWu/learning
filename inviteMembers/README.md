# 邀请成员

进入个人中心，点击邀请成员加入按钮，在弹窗内输入想要邀请成员的用户名，点击确认即可。

![](http://193.112.34.232:91/assets/img/intro/intro-20.gif)

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