**Week challenges (Tuesday)**

<br>

1. ### Start this HTML course

<br>

    1. Introduction to HTML


>*Working on it!*

<br>

2. ### Multiply exercise.

<br>

- Multiply two or more values, x * y. For matrices, the matrix product is calculated.

```JavaScript

Examples 
math.multiply(4, 5.2)        // returns number 20.8
math.multiply(2, 3, 4)       // returns number 24

const a = math.complex(2, 3)
const b = math.complex(4, 1)
math.multiply(a, b)          // returns Complex 5 + 14i

const c = [[1, 2], [4, 3]]
const d = [[1, 2, 3], [3, -4, 7]]
math.multiply(c, d)          // returns Array [[7, -6, 17], [13, -4, 33]]

const e = math.unit('2.1 km')
math.multiply(3, e)          // returns Unit 6.3 km
```

```JavaScript
function multiply(a, b) {
  let c = a * b;
  return c;
}
```

3. ## ASCII Total

<br>

- What ASCII means?

<br>

- American Standard Code for Information Interchange.

- ASCII (American Standard Code for Information Interchange) is the most common character encoding format for text data in computers and on the internet. In standard ASCII-encoded data, there are unique values for 128 alphabetic, numeric or special additional characters and control codes.

```JavaScript

function uniTotal (str) {
  let total = 0
for (let i = 0; i < str.length; i++){
 total += str[i].charCodeAt();
} 
  return total;  
}
undefined
uniTotal("aaa")
291
```








