# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```py
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="411" height="76" alt="image" src="https://github.com/user-attachments/assets/c398b795-6086-471b-b193-2a0f5daabca4" />

<img width="457" height="66" alt="image" src="https://github.com/user-attachments/assets/2dbb2526-4396-41be-9be4-187f44958d88" />

## Result
Thus, the program was executed successfully.
