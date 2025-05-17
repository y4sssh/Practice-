
num1 = int(input("Enter a first number : "))
num2 = int(input("Enter a second number : "))
num3 = int(input("Enter a third number : "))


if num1>num2 and num1>num3:
  print(f"First number ({num1}) is the largest.")
elif num2>num1 and num2>num3:
  print(f"Second number ({num2}) is the largest.")
else:
  print(f"Third number ({num3}) is the largest.")
