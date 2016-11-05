#Ti.SamsungPass

Titanium module for accessing Samsungs Pass (fingerprint sensor). You can it use additional to Ti.TouchId

Pass SDK allows you to use fingerprint recognition features in your application. With Pass SDK, you can provide reinforced security, by identifying whether the current user is the actual owner of the device.

<img src="http://developer.samsung.com/sd2_images/galaxy/content/sms_pass_03.jpg" width=400 />
##Usage

```javascript
var Spass = require("ti.samsungpass");
Spass.init();
Spass.addEventListener("result",function(){
	console.log(arguments[0]);
});

```