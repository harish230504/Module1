
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
# Boolean and Arithmetic Expressions with True and False

# Arithmetic operations
print("Arithmetic Operations:")
print("True + True =", True + True)       # 1 + 1 = 2
print("True + False =", True + False)     # 1 + 0 = 1
print("False + False =", False + False)   # 0 + 0 = 0
print("True * False =", True * False)     # 1 * 0 = 0
print("True * True =", True * True)       # 1 * 1 = 1
print("False - True =", False - True)     # 0 - 1 = -1

# Boolean operations
print("\nBoolean Operations:")
print("True and False =", True and False)
print("True or False =", True or False)
print("not True =", not True)
print("not False =", not False)

# Mixed expressions
print("\nMixed Expressions:")
print("(True + True) > False =", (True + True) > False)
print("(True * 5) == 5 =", (True * 5) == 5)
print("(False + 10) < 5 =", (False + 10) < 5)

## Output
## Result
