# python2
#swapping tech

#turple swapping(method 1)
a=1
b=2
a,b=b,a
print(a)
print(b)

#temporary variable(method 2)
a=-199
b=288
temp=a
a=b
b=temp
print(a,b)

#temporary variable with dynamic(method 3)
a=int(input("enter a value:"))
b=int(input("enter b value:"))
temp=a
a=b
b=temp
print(a,b)


#mathamathically(method 4)
a=int(input("enter a value:"))
b=int(input("enter b value:"))
a=a+b
b=a-b
a=a-b
print("after swapping")
print("a:",a)
print("b:",b)

#USING EX-OR (METHOD 5)
a=int(input("enter a value:"))
b=int(input("enter b value:"))
a=a+b
b=a-b
a=a-b
print("after swapping")
print("a:",a)
print("b:",b)
