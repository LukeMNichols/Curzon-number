# Curzon-number
First python code, very simple just finding whether a number is a Curzon number (2^n + 1) 


from random import randint
import math



def func(x):
    t = x - 1
    h = math.log(t,2)
    return h

x = int(input("What is your number?"))
if func(x) % 1 == 0:
    print("Curzon number")
else:
    print("Not curzon number")
    
