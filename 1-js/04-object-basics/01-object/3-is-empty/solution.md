<<<<<<< HEAD
単にオブジェクトをループし、少なくとも1つプロパティがある場合にはすぐに `return false` を返します。

```js
function isEmpty(obj) {
  for (let key in obj) {
    return false;
  }
  return true;
}
```
=======
Just loop over the object and `return false` immediately if there's at least one property.
>>>>>>> 1edb0a38330b54d2e1916f5193fc043e6fbbea78
