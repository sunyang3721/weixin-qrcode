# weixin-qrcode
微信二维码生成插件，需要加载jquery
```javascript
<script type="text/javascript" src="./js/jquery.qrcode.min.js"></script>
$(function(){
			$('#qrcode').qrcode("内容或链接");  //注意 中文可能会乱码
		});
```
```html
  <div id="qrcode"></div>
```
