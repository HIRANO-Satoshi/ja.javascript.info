
```js run
let array = [1, 2, 3];

array = new Proxy(array, {
  get(target, prop, receiver) {
    if (prop < 0) {
<<<<<<< HEAD
      // arr[1] のようにアクセスしても
      // prop は文字列なので、数値に変換する必要があります
=======
      // even if we access it like arr[1]
      // prop is a string, so need to convert it to number
>>>>>>> 8d9ecb724c7df59774d1e5ffb5e5167740b7d321
      prop = +prop + target.length;
    }
    return Reflect.get(target, prop, receiver);
  }
});


alert(array[-1]); // 3
alert(array[-2]); // 2
```
