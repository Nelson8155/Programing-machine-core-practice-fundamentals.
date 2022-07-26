**Week challenges (Thursday)**

1. ### Print special numbers

<br>

- Description

- In this exercise you must use an iterative flow control to be able to print all the even numbers in the range of numbers from 0 to 100. Remember that you should not print each number, you should use a flow control structure to perform the exercise.

<br>

>*Exercise with FOR*

```JavaScript

for (let i = 0; i <= 100; i++) {
 if(i % 2 == 0) console.log(i);
}
```

>*Exercuse with WHILE*

```JavaScript

var i = 0;
while (i <= 100) {
  if (i % 2 == 0) console.log(i);
  i++;
}
```
>*Excercise with do...while*

```JavaScript

var i = 0;
do {
  if(i % 2 == 0)console.log(i);
  i++
} while (i <=100)
```
<br>

2. ### Bad code

<br>

- Description

- The code shown below is not working in the right way, as a task you must find the error made by the developer who programmed this code and correct it, for this exercise you must explain what the error is and place the correct code.

```JavaScript

var cond = false;

if ((cond)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
VM156:6 The cond variable is false
```

<br>

3. ### Bad code 2

<br>

- Description

- You must create the code that follows the following logic, if the given number is 100, take this number as special and show the following message: "This is a special number!", but if the number is less than 1000, multiple of 10 and different from 100, you must show the following message: "This number is almost special". if none of the given conditions are met show the following message: "Just a regular number". Another developer was trying to program the logic, but apparently couldn't, you need to fix the code to work properly.

```JavaScript

var n = 100;

if (n == 100) {
  console.log('This is a special number!');
} else if (n < 1000 && n % 10 == 0) {
  console.log('This number is almost special');
} else {
  console.log('Just a regular number');
}
```

