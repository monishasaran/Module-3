## 1.List Operations in Python: Sum of List Items

🎯 Aim:

To write a Python program that calculates the sum of all elements in a list.

🧠 Algorithm:

Define a list of numbers.
Use Python’s built-in sum() function to calculate the total.
Print the result.

🧾 Program
```
list1=[1, 2, -8]
total=sum(list1)
print(total)
```
Output:

<img width="335" height="164" alt="{BC4C3EB2-945B-42C6-9D16-BCB1DB991AF7}" src="https://github.com/user-attachments/assets/2db48f6f-8d09-485c-8160-e994b83e7e37" />

Result:

Thus a Python program that calculates the sum of all elements in a list has been executed successfully.

## 2.Regex in Python: Filter Words Without the Letter 'e'

🎯 Aim
 
 To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

🧠 Algorithm:

Import the re module.
Initialize an empty list l1 to store results.
Define a list of words:
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
Iterate through each word in the list:
Use re.search(r"e", i) to check if the word contains 'e'.
If not, append the word to l1.
Print the final filtered list.

🧾 Program
```
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

result = [word for word in items if 'e' not in word]
print(result)
```

Output:

<img width="592" height="173" alt="WhatsApp Image 2026-06-01 at 9 31 03 AM" src="https://github.com/user-attachments/assets/1b89d8c6-7595-4b26-a129-6178894b14e0" />

Result:

Thus a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) has been executed successfully.

## 3.Strings-Remove Nth Index Character from a String

🎯 Aim:

To write a Python program that accepts a string and removes the character at a specified index.

🧠 Algorithm:

Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.

💻 Program
```
def remove(s):
    n = int(input())
    c=s[:n] + s[n+1:] 
    print(c)
```

Output:

<img width="656" height="206" alt="{B03C0E65-9260-45E8-8780-CDA8C54C2D31}" src="https://github.com/user-attachments/assets/7fb82cf9-2990-460d-972e-78aded0c71df" />

Result:

Thus a python program that accepts a string and removes the character at a specified index has been executed successfully.

## 4.Strings-Palindrome Check in Python (Without Built-in Functions)

🎯 Aim

To write a Python program to check whether the string "malayalam" is a palindrome or not, without using built-in palindrome checking functions.

🧠 Algorithm

Assign the string "malayalam" to a variable.
Reverse the string manually using slicing ([::-1]).
Compare the original string with the reversed string.
If they are equal, print that the string is a palindrome.
Otherwise, print that it is not a palindrome.
Execute the program.

🧾 Program
```
text = input()

rev = text[::-1]

if text == rev:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

Output:

<img width="902" height="238" alt="{4D69A84B-5BC5-44EA-AC7D-7ABCBD6C7FFF}" src="https://github.com/user-attachments/assets/72706a5f-f63e-40fe-9d0f-a7b16f9b6098" />

Result:

Thus a Python program to check whether the string is a palindrome or not, without using built-in palindrome checking functions has been executed successfully.

## 5.Tuple in Python: Check Element Existence

🎯 Aim

To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

🧠 Algorithm

Define a tuple x with some letters and numbers.
Use the in operator to check if the string 'n' exists within the tuple.
Use the in operator to check if the integer 8 exists within the tuple.
Print the results.

🧾 Program
```
tuplex = ("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in tuplex)
print( 8 in tuplex)
```

Output:

<img width="498" height="199" alt="WhatsApp Image 2026-06-01 at 9 48 52 AM" src="https://github.com/user-attachments/assets/6399446f-30c3-4724-8779-403eefd8c5dd" />



Result:

Thus a Python program that checks if the element 'n' and the element 8 exist within a given tuple has been executed successfully.
 
