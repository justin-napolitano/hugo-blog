+++
title = "Testing IFrame "
date = 2022-04-15
draft = false
+++

<head>
<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>
</head>
<iframe src="european-gas-imports.html" frameborder="0" scrolling="no" onload="resizeIframe(this)"></iframe>