importance: 5

---

# スパムのチェック

<<<<<<< HEAD
もし `str` に 'viagra' または 'XXX' を含む場合には `true` を、それ以外の場合には `false` を返す関数 `checkSpam(str)` を書きなさい。
=======
Write a function `checkSpam(str)` that returns `true` if `str` contains 'viagra' or 'XXX', otherwise `false`.
>>>>>>> d5e8b6d308869738bd1f08dde62b64c969b0673e

この関数は大文字と小文字を区別する必要はありません。:

```js
checkSpam('buy ViAgRA now') == true
checkSpam('free xxxxx') == true
checkSpam("innocent rabbit") == false
```
