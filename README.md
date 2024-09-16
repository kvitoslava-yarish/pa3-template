# pa3 tasks

## Task 1: Pattern Construction

Write a Python program to construct the following pattern using a nested `for` loop:
```
* 
* * 
* * * 
* * * * 
* * * * * 
* * * * 
* * * 
* * 
*
```
---

## Task 2: Reverse a Word

Write a program that accepts a word from the user and reverses it.

---

## Task 3: Count Even and Odd Numbers

Write a program to count the number of even and odd numbers in a series of numbers.

**Sample numbers**:  
`numbers = (1, 2, 3, 4, 5, 6, 7, 8, 9)`

**Expected Output**:
- Number of even numbers: 5
- Number of odd numbers: 4

---

## Task 4: Count Letters and Digits

Write a program that accepts a string and calculates the number of digits and letters.

**Sample Data**:  
`Python 3.12`

**Expected Output**:
- Letters: 6
- Digits: 3

---

## Task 5: Skip Numbers 3 and 6

Write a Python program that prints all the numbers from 0 to 6, except 3 and 6.  
**Note**: Use the `continue` statement.

**Expected Output**:
- `0 1 2 4 5`

---

## Task 6: Password Validation

Write a Python program to check the validity of passwords input by users.

**Validation Requirements**:
- At least 1 letter between `[a-z]` and 1 letter between `[A-Z]`
- At least 1 number between `[0-9]`
- At least 1 character from `[$#@]`
- Minimum length: 6 characters  
- Maximum length: 16 characters

---
**Hint for task 1**
```
n = 5
for i in range(n):
    for j in range(i):
```
