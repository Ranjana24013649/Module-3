# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

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
Add Code Here
n=int(input())

def remove(a):

    for i in range(0,len(a)):
    
        if(i!=n):
        
            print(a[i],end='')


## Output

![440091991-2258529b-4a21-4919-a49f-223312bc4fba](https://github.com/user-attachments/assets/561af94b-e8a7-4381-97ce-896067755ea8)


## Result

Thus the python program is executed successfully
