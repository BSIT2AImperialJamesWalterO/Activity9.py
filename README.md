# Activity9.py
name = input("Please enter your name --> ")
age = input("Please enter your age --> ")
try:
  age = int(age)
  if age < 18:
    print(f"Hello, {name}, You are a minor")
  elif age >= 18 and age < 65:
    print(f"Hello, {name}, You are an adult")
  else:
    print(f"Hello, {name}, You are a senior citizen.")
except ValueError:
  print("Invalid age input. Please enter a number.")
