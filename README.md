```js
  truncate('when shall we three meet again', 9); // 'when s...'
  truncate('when shall we three meet again', 10, ' (etc)'); // 'when (etc)'
  truncate('when shall we', 15,); // 'when shall we'
  truncate('when shall we', 15, '(more)'); // 'when shall we'
  truncate('when shall we', 10, ' (etc etc etc)'); // ' (etc etc etc)'
```
