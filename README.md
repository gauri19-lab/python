PYTHON PROGRAMMING
1.Write a program to output the squares (using multiplication) of numbers from 1 to 5 on separate lines.
print(1,"-",1*1)
print(2,"-",2*2)
print(3,"-",3*3)
print(4,"-",4*4)
print(5,"-",5*5)


Write a program to output the square of * (stars) of size 4
print("*" *  4)
print("*" *  4)
print("*" *  4)
print("*" *  4)

"""x, y, z = "Orange", 123, # "Cherry"
print(x)
print(y)
print(z)
print(type(y))"""



"""
x = y = z = "Orange"
print(x)
print(y)
print(z)

a = ["apple", "banana", "cherry"]
x, y, z = a
print(x)
print(y)
print(z)
"""
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
x = "Python"
y = "is"
z = "awesome"
print(x+ y+ z)

"""a=1
b="hello"
print(a+b)"""


x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()




x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)


x = "awesome"

def myfunc():
  global x
  x = "fantastic"
  print("reeti is " + x)
myfunc()
print("gauri is " + x)



x=20
y=6
print(x//y)
print(x/y)
print('--------------------------------------')
temperature=25.5
y=25.5+273
print('Celsius -',temperature)
print('Kelvin -',y)
print('------------------------------------------------------------')
x=4.5*4.5
y=4*4.5
print('Area of a Square =',x)
print('perimeter =',y)
x=4.5
area=x*x
perimeter=4*x
print(area)
print(perimeter)
print('------------------------------------------------------------------------')







x=20
y=6
print(x//y)
print(x/y)
print('--------------------------------------')
temperature=25.5
y=25.5+273
print('Celsius -',temperature)
print('Kelvin -',y)
print('------------------------------------------------------------')
x=4.5*4.5
y=4*4.5
print('Area of a Square =',x)
print('perimeter =',y)
x=4.5
area=x*x
perimeter=4*x
print(area)
print(perimeter)
print('------------------------------------------------------------------------')
x = 1
y = 356562225548877112457896325648456612378945674136985265431978625
z = -3255522

print(type(x))
print(type(y))
print(type(z))

print('-----------------------------------------------------------------------------')

x = 1.1056897412589632659784512
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))
print('------------------------------------------------------------------------')
x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))
print('--------------------------------------------------------')
x = 3+5j
y = 5J
z = -5j

print(type(x))
print(type(y))
print(type(z))
print('------------------------------------------------------------------------')
x = 1    # int
y = 2.8  # float
z = 1j   # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(y)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
print('----------------------------------------------------------------------------')
import random

print(random.randrange(16, 100))



