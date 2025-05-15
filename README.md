# STRING OPERATIONS AND ITS FUNCTION
# AIM:
To write a python program to capitalize every alternative sting.

# ALGORITHM:
🔄 Steps:

1)Initialize a counter d to 1.

2)For each character i in the input string a, do:

If d is even (i.e., d % 2 == 0):

Convert character i to uppercase.

3)Print the uppercase character without a newline.

Else:

Print character i as it is without a newline.

4)Increment the counter d by 1.

5)End loop.

# PROGRAM:
```
def convert(a):
    d=1
    for i in a:
        if d%2==0:
            b=i.upper()
            print(b,end="")
            d+=1
        else:
            
            print(i,end="")
            d=d+1
  ```
# OUTPUT:
![image](https://github.com/user-attachments/assets/bc028b98-cfa1-4b48-8348-37f7749000f5)

# RESULT:
Thus expected output is acheived


