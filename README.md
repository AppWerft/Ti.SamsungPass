#Ti.SamsungPass

Titanium module for accessing Samsungs Pass (fingerprint sensor). You can it use additional to Ti.TouchId

##Usage

```javascript
var Spass = require("ti.samsungpass");
Spass.init();
Spass.addEventListener("result",function(){
	console.log(arguments[0]);
});

```