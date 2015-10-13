# Countdown exercise

Make a kitchen timer.  Modify the `countdown()` function in [countdown.js](countdown.js) to take a number of seconds, then print each second counting down to zero.

```javascript
countdown(10);

// should print

// 10...
// 9...
// 8...
// ...
```

## Levels

1. Use global variable to keep track of time
1. Keep track of time *without* defining any global variables
1. Don't define any new variables
1. Refactor `countdown` so that you can pass in a callback function that fires every second.

Here is an example of the fourth level:

```js
countdown(10, function (i) {
  console.log('THIS IS MY CUSTOM CALLBACK!!!', i);
});
```


## Documentation

* [`setTimeout()`]( https://developer.mozilla.org/en-US/docs/DOM/window.setTimeout)
* [`setInterval()`](https://developer.mozilla.org/en-US/docs/DOM/window.setInterval)
* [`clearInterval()`](https://developer.mozilla.org/en-US/docs/Web/API/window.clearInterval)
