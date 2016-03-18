
# False but True

```js
var fBoolean = new Boolean(false);
if(!fBoolean) {
  // Oops never comes here
}
```

##Reason
Because fBoolean is object wrapper with false value and is always true.
