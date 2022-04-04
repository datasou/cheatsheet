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
## Containers
### Container types
- list e.g. [1, 2, 2, 3], ["val1", "val2"]
- tuple e.g. (1, 2, 2), ("val1", "val2")
- dict e.g. {"key1": "val1", "key2": "val2"}
- set e.g. {1,2,3}, {"key1", "key2"}
### Generic operations
```python
len(c)  # items count
min(c), max(c)  # min and max value
sum(c)  # get sum value
sorted(c)  # sorted copy
val in c  # check if val in c
enumerate(c)  # iterate on (index, val)
zip(c1, c2, ...)  # (c11, c21), (c12, c22), ...
all(c)  # True if ALL elements in c are True
any(c)  # True if ANY elements in c are True
# Note: keys are used for dict and set
```
### List
```python
lst = [1, 2, -5, 6]  # init
lst.append(val)  # add val to lst
lst.extend(lst2)  # add lst2 at the end of lst
lst.insert(idx, val)  # add val at idx
lst.remove(val)  # remove first val in lst
lst.pop(idx)  # pop val at idx
```
## Dictionary
```python
dct = {"A": "hello", "B": "world"}  # init with keys and vals
dct[key] = val  # set val at key
dct[key]  # get val by key
dct.update(dct2)  # update dct with dct2
dct.keys()  # get all keys
dct.values()  # get all vals
dct.items()  # get all (key, val)
dct.pop(key)  # get val by key and pop key
dct.popitem()  # pop (key, val)
dct.get(key, default)  # get val by key, return default if not exist
```
## Set
```python
s1 = {"A", "B"}; s2 = {"B", "C"}  # init
s1 | s2  # union {"A", "B", "C"}
s1 & s2  # intersect {"B"}
s1 - s2  # difference {"A"}
s1 ^ s2  # symmetric diff {"A", "C"}
s1.update(s2)  # s1 | s2 and update to s1
s1.add(key)  # add key to s1
s1.remove(key)  # remove key from s1
s1.discard(key)  # remove key from s1 if exist
s1.pop()  # pop a key from s1
```
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
```python
abs(-1.2)  # 1.2
round(3.14, 1)  # 3.1
pow(2, 3)  # 8
```
### math modules
- import: `from math import ...`
- functions: `sin, cos, sqrt, log, ceil, floor`
## Display
```python
print("text1", val, "text2")
print("text1 " + val + " text2")
print(f"text1 {val} text2")
print(f"text1 {val} text2")
print("{:.2f}".format(1.123456))  # 1.12
```
## Input
```python
s = input("input value:")
```
