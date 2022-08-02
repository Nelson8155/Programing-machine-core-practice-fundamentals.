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

2. ### Vowel Remover exercise.

<br>

```JavaScript

function shortcut(string) {
  let result = '';
  for (let i = 0; i < string.length; i++) {
    if (
      string[i] == 'a' ||
      string[i] == 'e' ||
      string[i] == 'i' ||
      string[i] == 'o' ||
      string[i] == 'u'
    ) {
      continue;
    }
    result = result + string[i];
  }
  return result;
}
```

3. ### Rock Paper Scissors! exercise

<br>

```JavaScript

const rps = (p1, p2) => {
 if (p1 == "rock" && p2 == "scissors") {
   return "Player 1 won!";
 }else if (p1 == "scissors" && p2 == "paper"){
   return "Player 1 won!";
 }else if (p1 == "paper" && p2 == "rock"){
   return "Player 1 won!";
 }else if (p1 == p2){
   return "Draw!";
 }else {
   return "Player 2 won!";
 }
}
```

4. ### Persistent Bugger exercise.

<br>

```JavaScript

function persistence(num) {
  let times = 0;
  let digits = [];
  while (num >= 10) {
    digits = num.toString().split('');
    num = 1;
    for (let i = 0; i < digits.length; i++) {
      num *= digits[i];
    }
    times++;
  }
  return times;
}
```
