**Week challengers (Wednesday)**

<br>

1. ### Your date of birth in the matrix?
<br>

- Description: Your team has just seen the movie "Matrix" and you have been asked, how the number of your year of birth would be written in binary. You must learn how to translate your date of birth into binary and show your team. (Do not use a webpage or a tool to convert your date of birth)

<br>

>Solution

- Year 1996

2.10 - 2.09 - 2.08 - 2.07 - 2.06 - 2.05 - 2.04 - 2.03 - 2.02 - 2.01

<br>

***Binary code***

  1 1 1 1 1 0 0 1 1 0 = 1996

<br>

***Excersice***

<br>

| Binary      | Value       | Result 1996 - VALUE    
| ----------- | ----------- | -----------
| 2.10        | 1024        | 972
| 2.09        | 512         | 460
| 2.08        | 256         | 204
| 2.07        | 128         | 76
| 2.06        | 64          | 12
| 2.03        | 8           | 4
| 2.02        | 4           | 0

![Binary code!](binary-code-4437421_640.jpg)

<br>

2. ### MIPS Exercise.

<br>

Create a program that adds any two given numbers provided by the user

Create a program that displays your name

<br>

```assembly

  .data
        message: .asciiz "\nNelson, Beltran!\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall
```


```assembly

  .data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
	      result_message: .asciiz "\nEl resultado es: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t2, $v0

              li $v0, 1
              move $a0, $t0
              syscall

              li $t0, 10
              li $t1, 10

              add $t2, $t0, $t1

              li $v0, 4
              la $a0 result_message
              syscall

              li $v0, 1
              move $a0, $t2
              syscall
              
```
