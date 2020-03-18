# 修改用户昵称

进入个人中心，在用户昵称的编辑框内填入想要修改的昵称，点击后面的保存按钮即可。

![](http://193.112.34.232:91/assets/img/intro/intro-22.gif)

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