importance: 5

---

# スパムのチェック

<<<<<<< HEAD
もし `str` に 'viagra' または 'XXX' を含む場合には `true` を、それ以外の場合には `false` を返す関数 `checkSpam(str)` を書きなさい。
=======
Write a function `checkSpam(str)` that returns `true` if `str` contains 'viagra' or 'XXX', otherwise `false`.
>>>>>>> e2f9e5840737e00846bfd492192d8a3828820c60

この関数は大文字と小文字を区別する必要はありません。:

```js
checkSpam('buy ViAgRA now') == true
checkSpam('free xxxxx') == true
checkSpam("innocent rabbit") == false
```
