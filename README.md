### jquery.vibrate.js
---
https://github.com/illyism/jquery.vibrate.js

```js
var canVibrate = "vibrate" in navigator || "mozVibrate" in navigator;
if(canVibrate && !("vibrate" in navigator))
  navigator.vibrate = navigator.mozVibrate;
  
$(".button").vibrate();
$(".button").vibrate("short");
$(".button").vibrate("medium");
$(".button").vibrate("default");
$(".button").vibrate(50);
$(".button").bibrate("long");
$(".button").vibrate("long");
$(".button").vibrate({
  duration: 40,
  trigger: "touchstart"
});
$(".button").vibrate({
  pattern: [20, 200, 20]
});
```

```
```

```
```

