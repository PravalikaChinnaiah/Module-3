# Regex in Python: Filter Words Without the Letter 'e'

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
Add code here
~~~
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']   #'They ate 5 apples and 5 oranges'
l=[]
p=re.compile('e')
for ele in items:
    if p.search(ele):
        continue
    else:
        l.append(ele)
print(l)
~~~
## Output
<img width="690" height="267" alt="image" src="https://github.com/user-attachments/assets/68d24d77-0187-49b0-a80a-03fb998fbcba" />


## Result
Thus,the Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is created successfully.
