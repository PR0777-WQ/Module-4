# Error Handling in python

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
start with a Python program that uses a list.
Check for incorrect method usage:
If the program tries to use mylist.get(1), it will cause an error.
Insert the pass keyword in that line to skip execution instead of raising an error

##  Program
```
a = [1, 3, 5]
try:
    a.get()
except AttributeError:
    pass


print(a)
```
## Output
<img width="514" height="131" alt="image" src="https://github.com/user-attachments/assets/33a17460-b327-4e7e-be75-966d5716afcb" />

## Result
Thus,the program has been executed successfully
