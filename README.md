# Cramer-s-Rule
#Open in Python
#Studying in 10th standard ; maybe Maharashtra board of India then you are on the right page take this code open and get answers.
#CRAMERS RULE 10TH STD
#all imports
import math
from fractions import Fraction

print("Please Enter correct value and only integers and "
      "press enter for subbmission")
a1 = input("Enter the value of A1 ")
print("value of a1 is " + a1)
a2 = input("Enter the valur of A2 ")
print("value of a2 is " + a2)
b1 = input("Enter the value of B1 ")
print("value of b1 is " + b1)
b2 = input("Entr the value of B2 ")
print("value of b2 is " + b2)
c1 = input("Enter the value of C1 ")
print("value of c1 is " + c1)
c2 = input("Enter the value of C2 ")
print("value of c2 is " + c2)
input("Press enter to continue ")
print("This calculation may take time so sit back and relax for your answer")

#Calculations for sum

d = (int(a1) * int(b2)) - (int(b1) * int(a2))

dx = (int(c1) * int(b2)) - (int(b1) * int(c2))
dy= (int(a1) * int(c2)) - (int(c1) * int(a2))
x = (int(dx) / int(d))
y = (int(dy) / int(d))



# Prints

print("the value of d is ")
print(d)
print("the value of dx is ")
print(dx)
print("the value of dy is ")
print(dy)
print("Note:")
print("      The values of x and y will be in the fraction form")
print("the value of x is ")
print(Fraction(x))
print("the value of y is ")
print(Fraction(y))

