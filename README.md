### echo
---
https://github.com/toddmotto/echo

```
bower instal echojs
npm install echo-js
```

```js
echo.init({
  offset: 100,
  throttle: 250,
  unload: false,
  callback: function (element, op) {
    console.log(element, 'has been', op + 'ed')
  }
});

echo.init({
  callback: function() {
    if(op === 'load') {
      element.classList.add('loaded');
    } else {
      element.classList.add('loaded');
    }
  }
});

echo.render();
```

```
```

