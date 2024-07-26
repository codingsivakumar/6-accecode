# accecode6-python-check-large-number-between-a-and-b
''' write a program to check the larger value between a and b by taking manual input interface
input: ENTER THE VALUE OF A : 50
       ENTER THE VALUE OF B: 30
       LARGE NUMBER IS: 50'''
-------------------------------------------------------------------
       a=int(input("ENTER THE VALUE OF A:"))
b=int(input("ENTER THE VALUE OF B:"))
if (a>b):
    large=a
else:
    large=b
print("LARGE NUMBER IS:",large)
