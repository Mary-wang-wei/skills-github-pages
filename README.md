<!DOCTYPE html>
<html>
<head>
  <title>随机问卷</title>
  <script>
    function redirect() {
      // 定义三份问卷的链接
      var urls = [
        "https://www.wjx.cn/vm/PpqXlXP.aspx#",
        "https://www.wjx.cn/vm/PLcDvyE.aspx#",
        "https://www.wjx.cn/vm/eSB9Xaf.aspx# "
      ];
      // 随机选择一个链接
      var randomUrl = urls[Math.floor(Math.random() * urls.length)];
      // 跳转到随机选择的问卷链接
      window.location.href = randomUrl;
    }
  </script>
</head>
<body onload="redirect()">
  <p>正在跳转，请稍候...</p>
</body>
</html>
