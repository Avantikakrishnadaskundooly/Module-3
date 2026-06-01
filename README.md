# Ex 1:List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```py
items=[153,147,124,102]
print(sum(items))
```

## Output
<img width="161" height="47" alt="image" src="https://github.com/user-attachments/assets/a15005f3-3859-458a-a1dc-6f76353ad300" />

## Result
Thus, the program was executed successfully.




# Ex 2:Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```py
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```

## Output
<img width="416" height="57" alt="image" src="https://github.com/user-attachments/assets/b5dfa05f-2e60-49d0-bdc2-55c323a1d84c" />

## Result
Thus, the program was executed successfully.




# Ex 3:🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```py
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
remove("learning")
```

## Output
<img width="191" height="63" alt="image" src="https://github.com/user-attachments/assets/dd105619-9546-40d4-985f-6ca8b6c843c0" />

## Result
Thus, the program was executed successfully.




# Ex 4:Strings-Palindrome Check in Python (Without Built-in Functions)

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
