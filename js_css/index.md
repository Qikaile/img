---
title: 相册
noDate: 'true'
comments: 'false'
abbrlink: '9924'
photos: 
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Qikaile/img/js_css/ins.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Qikaile/img/js_css/photoswipe.css"> 
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Qikaile/img/js_css/default-skin/default-skin.css"> 
<script src="https://cdn.jsdelivr.net/gh/Qikaile/img/js_css/photoswipe.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/Qikaile/img/js_css/photoswipe-ui-default.min.js"></script>
<div class="photos-btn-wrap">
	<a class="photos-btn active" href="javascript:void(0)">Photos</a>
	<a class="photos-btn" href="#">待续</a>
</div>
<div class="instagram itemscope">
	<a href="https://github.com/Qikaile/img/photos" target="_blank" class="open-ins">图片正在加载中…</a>
</div>
<script>
  (function() {
    var loadScript = function(path) {
      var $script = document.createElement('script')
      document.getElementsByTagName('body')[0].appendChild($script)
      $script.setAttribute('src', path)
    }
    setTimeout(function() {
      loadScript('https://cdn.jsdelivr.net/gh/Qikaile/img/js_css/ins.js')
    }, 0)
  })()
</script>