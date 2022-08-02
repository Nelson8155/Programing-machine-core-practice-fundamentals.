**Week challenges (Thursday)**

1. ### Remove All Exclamation Marks From The End Of Sentence exercise.

<br>

```JavaScript
function remove(string) {
  let result = '';
  let lastValidStringPosition = string.length - 1;
  for (let i = lastValidStringPosition; i > 0; i--) {

    if (string[i] !== '!') {
      result = string.substring(0, i + 1); // saving the remaining characters
      break; // we should stop the search
    }
  }
  return result;
}
```

2. ### 