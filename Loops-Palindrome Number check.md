## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```c

num = int(input("Enter a number: "))
original = num
reversed_num = 0

while num > 0:
    digit = num % 10            
    reversed_num = reversed_num * 10 + digit  
    num = num // 10             
if original == reversed_num:
    print(original, "is a Palindrome number.")
else:
    print(original, "is NOT a Palindrome number.")
```
## Output
<img width="332" height="50" alt="image" src="https://github.com/user-attachments/assets/a9a2b740-17dd-4e16-88f9-83462858ab4c" />


## Result
Thus, the program has been executed successfully.
