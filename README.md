# Types Variables Logic and Operations Lab

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## 1. Which data type would be the best to use for recording the total balance of an online shopping cart?

Double would be a great data type to store the balance of an online shopping cart. Shopping cart balances use dollars and cents represented by decimal point numbers. 

***
## 2. Which of the following variable declarations is **incorrect**?

```swift
let isClosed: Bool = false

let version: Double = 3.0

let emotion: String = ":)"

let grade: Char = "a"
```

*Bool*, *Double*, *String* are all valid data types. If **Char** was changed to *Character* it would be a valid type too.

```swift
let grade: Char = "a"
``` 

***
## 3. Simplify the following using a calculator:

1 + 4 * 2 / 2 + 2

1 + **8** / 2 + 2

1 + **4** + 2

7

***
## 4. Which of the following are true? State all that apply.

```swift
17 % 4 == 1

25 % 4 != 1

81 % 9 != 840 % 2

(14 % 2 < 4) || (243 % 13 > 2) || (52 % 3 > 5)
```

17 div 4  is 4 w/ remainder of 1 : **True**

25 div 4 is 6 w/ remainder of 1 : **False**

81 div 9 is 9 w/ remainder 0 && 840 is even so its remainder when div 2 is 0 : **False**

14 is even so its remainder is 0 and that is less than 4 so statement is **True** because at least one OR term is true

***
## 5. Which of the follow is true?

a) **True**
```swift
let numOne = 4.0
let numTwo = 4.0
let a = numOne == numTwo
```
b) **False**
```swift
let numThree = 24/5
let numFour = 24.0/5.0
let b = numThree == numFour
```
c) **False**
```swift
let numFive = 24%5
let numSix = 24.0%5.0
let c = numFive == numSix
```
d) **False**
```swift
let numSeven = 4.0 + 1.2
let numEight = 5.0 + .2
let d = numSeven == numEight
```

***
## 6. What is the final value of i?

```swift
var i = 0
i = 5
i += 3
i *= 2
i %= 3
i -= 3
```
i = 0, i = 5, i = 8, i = 16, i = 1, i = -2

The final value of i is -2.
