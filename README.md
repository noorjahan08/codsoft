# calculator
calculator with basic arthemetic operations
print("Select an operator to perform:")
print("1.ADDITION")
print("2.SUBTRACTION")
print("3.MULTIPLICATION")
print("4.DIVISION")

operation = input()

if operation == "1":
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    print("The sum is " +str(a + b))
elif operation == "2":
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    print("The sum is " + str(a - b))
elif operation == "3":
     a = float(input("Enter first number: "))
     b = float(input("Enter second number: "))
     print("The sum is " + str(a * b))
elif operation == "4":
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    print("The sum is " + str (a / b))
else:
    print("Invalid ")
