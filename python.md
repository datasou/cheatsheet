# Build-in
## Base Types
- int  e.g. 0, -34, 223
- float e.g. 3.1416, 0.03, -1.23
- bool e.g. True, False
- str e.g. "Hello", "name"
- bytes e.g. b'\xe0\xb8\x88\xe0\xb8\xb4'
## Variable Assignment
```python
x = 10
x = y = z = 5
x, y = 5, 6
x += 1  # x = x + 1
x -=5  # x = x - 5
x = "Hello"
x = None
```
## Container Types
- list e.g. [1, 2, 2, 3], ["val1", "val2"]
- tuple e.g. (1, 2, 2), ("val1", "val2")
- dict e.g. {"key1": "val1", "key2": "val2"}
- set e.g. {1,2,3}, {"key1", "key2"}
## List
`lst = [1, 2, -5, 6]`
- `len(lst)  # 6`
- `min(lst)  # -5`
- `sorted(lst)  # [-5, 1, 2, 6]`
- `val in lst  # True if val exists in lst`
- `all(lst)  # True if ALL elements in lst are True`
- `any(lst)  # True if ANY elements in lst are True`
## Tuple
## Dictionary
## Set
## Conditional Statement
```python
if logic_condition:
    do_something1()
elif logic_condition2:
    do_something2()
else:
    do_something3()
```
## Loops
### Conditional
```python
while(logic_condition):
    do_something()
```
### Iterative
```python
for var in sequence:
    do_something(var)
```
### Loop control
- `break` - exit the loop
- `continue` - next iteration
## Maths
### Operations
- Operators: `+, -, *, /, //, %, **`
- `abs(-1.2) >>> 1.2`
- `round(3.14, 1) >> 3.1`
- `pow(2, 3) >> 8`
### math modules
- import: `from math import ...`
- functions: `sin, cos, sqrt, log, ceil, floor`
## Display
- `print("text1", val, "text2")`
- `print("text1 " + val + " text2")`
- `print(f"text1 {val} text2")`
- `print(f"text1 {val} text2")`
- `print("{:.2f}".format(1.123456))  # 1.12`
## Input
- `s = input("input value:")`
# numpy
-
# pandas