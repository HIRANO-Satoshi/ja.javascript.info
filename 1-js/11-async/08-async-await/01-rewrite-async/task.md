
# async/await を使用して書き直す

<<<<<<< HEAD:1-js/11-async/08-async-await/01-rewrite-async/task.md
チャプター <info:promise-chaining> にある例の1つを `.then/catch` の代わりに `async/await` を使って書き直してください。: 
=======
Rewrite this example code from the chapter <info:promise-chaining> using `async/await` instead of `.then/catch`:
>>>>>>> d5e8b6d308869738bd1f08dde62b64c969b0673e:1-js/11-async/08-async-await/01-rewrite-async/task.md

```js run
function loadJson(url) {
  return fetch(url)
    .then(response => {
      if (response.status == 200) {
        return response.json();
      } else {
        throw new Error(response.status);
      }
    });
}

loadJson('https://javascript.info/no-such-user.json')
  .catch(alert); // Error: 404
```
