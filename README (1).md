---
description: 와와 책을 만들어보아요
---

# 테스트용 페이지

책 제목

책 내용

책 끝



<figure><img src=".gitbook/assets/sys_msg_bg.png" alt=""><figcaption><p>THERE</p></figcaption></figure>

상상하는 그 세상, THERE



```javascript
	var options = { forceNew: true, secure: true, transports: ['websocket'] };
	var ServerAddr = window.location.protocol + "//" + window.location.hostname + ':' + window.location.port;

	var socket = io.connect(ServerAddr, options);

	socket.on('connect', function() {
		var userLeftMessage = '<p class="text-warning"><em> connect </em></p>';
		appendAndScroll(userLeftMessage);
	});

	socket.on('disconnect', function() {
		var userLeftMessage = '<p class="text-warning"><em> connection is closed .</em></p>';
		appendAndScroll(userLeftMessage);
	});
```





:clap:

## 아아아

{% hint style="info" %}
흰트를 줄까?
{% endhint %}

{% embed url="https://there.space" %}

{% embed url="https://youtu.be/7mw6Zc4KD_0?feature=shared" %}
강좌 개설하기
{% endembed %}
