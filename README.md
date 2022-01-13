# Calculator-with-Python
#This is my first ever project with python

a = int(input("first number: "))
b = int(input("second number: "))
op = input("operator: ")

if op =="+":
	print(a+b)
elif op=="-":
	print(a-b)
elif op=="*":
	print(a*b)
elif op=="/":
	print(a/b)
else:
	print("wrong input")
