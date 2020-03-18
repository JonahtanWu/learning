# 修改系统名称

鼠标移动到系统名称上，在名称旁边会出现一个编辑的icon，点击icon即可修改系统名称。

![](http://193.112.34.232:91/assets/img/intro/intro-19.gif)

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