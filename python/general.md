# General

## What is Python?

Python is a programming language :
- high-level;
- open source;
- object-oriented.

## Indentation

In Python, indentation is used to mark a block of code. In order to indicate a block of code, four spaces are required.

## Variables

A container that stores a data value. The variable value may change when program is running.
```
variableName = value
variableName1 = variableName2 = value
variableName1,  variableName2 = value1, value2
```

## Debug or comment

```
variableName = value
print(variableName)

x = """a multi-line text
enclosed by
triple quotes
"""
print(x)


# comment on one line

"""
A multi-line comment
Developer friendly text for describing the purpose of function
Some test cases used by different unit testing libraries
"""
```

## Arithmetic Operator

|Operator|Operation|Comment|
|---|---|---|
|+|addition||
|-|substraction||
|*|multiplication||
|/|division||
|//|integer division|works like "/" and returns the floor integer|
|%|remainder|modulus operator divides the first operand by the second operand, returns the remainder|
|**|exponentiation|returns the result of the first operand raised to the power of the second operand|

## Assignment Operators

|Operators|Examples|Equivalent|
|---|---|---|
|+=|x += y|x = x + y|
|-=|x -= y|x = x - y|
|*=|x *= y|x = x * y|
|/=|x /= y|x = x / y|
|%=|x %= y|x = x % y|
|//=|x //= y|x = x // y|
|**=|x **= y|x = x ** y|

## Comparison Operators

After using comparison operators, the result will be true or false.

|Operators|Running|
|---|---|
|>|greater than|
|<|less than|
|>=|greater than or equal|
|<=|less than or equal|
|==|equal|
|!=|not equal|

## Convert Data Type

|Function|Operation|
|---|---|
|int(x)|convert x to an integer number|
|str(x)|convert x to a string|
|chr(x)|convert x to a character|
|float(x)|convert x to a floating point number|
|hex(x)|convert x to a hexadecimal string|
|oct(x)|convert x to a an octal string|
|round(x)|round a floating-point number x|
|type(x)|detect x data type|

## If-elif-Statement

```
if <test-expression>:
    ...
elif <test-expression>:
    ...
else:
    ...
```

## Loops

```
for var in range(n)
    # generates a sequence from 0 to n-1.

for var in range(n1, n2)
    # generates a sequence from n1 to n2-1.

while <test-expression> :
    ...
```

"break" keyword is used to stop the running of a loop according to the condition.

## Inputs

```
variable = raw_input("prompt")
```

Be careful: raw_input() does not exist in Python 3.x, while input() does. Actually, the old raw_input() has been renamed to input(), and the old input() is gone, but can easily be simulated by using eval(input()).


## Math functions

Be careful: "import math" before using the math function.

|Function|Description|
|---|---|
|abs(n)|absolute value of n|
|round(n)|round off a floating number n|
|ceil(n)|ceiling of n|
|floor(n)|flooring of n|
|max(n, m)|largest of n and m|
|min(n, m)|smallest of n and m|
|degrees(n)|convert n from radians to degrees|
|log(n)|base  e logarithm of n|
|log(n, m)|base m logarithm of n|
|pow(n, m)|n to the power of m|
|sqrt(n)|square root of n|
|sin(n)|sine of n|
|cos(n)|cosine of n|
|tan(n)|tangent of x|

## Functions

```
def functionName(): # define a function
    function body

functionName() # call a function
```

```
def functionName(arguments): # define a function
    function body

functionName(arg) # call a function
```

```
def main ():
    default start point of the whole program.
```

## List

An array in Java, a series of data.

```
listName = [val1, val2, val3]
```

|Function|Description|
|---|---|
|list.append(n)|Append n to the end of list|
|list.count(n)|Count how many n|
|list.index(n)|Return the index of n|
|list.insert(i,n)|Insert n before index i|
|list.pop(i)|Remove & return the item at index i|
|list.remove(n)|Remove the n|
|list.reverse()|Reverse the sequence of list|
|list.sort()|Sort the element of list increasingly|
|list1 + list2|concatenate two lists|
|len(list)|return the length of the list|

## Tuple

A tuple is a collection which is ordered and unchangeable.

```
aTuple = ("apple", "banana", "cherry")
print(aTuple)
```

|Function|Description|
|---|---|
|x in tpl|return true if x is in the tuple|
|len(tpl)|return length of the tuple|
|tpl.count(x)|count how many x in tuple|
|tpl.index(x)|return the index of x|


## Set

Set’s value is unique; it is a special list whose value is unique.

```
selectOptions = {"dog", "cat", "rat"}
```

|Function|Description|
|---|---|
|set.add(n)|add x to the set|
|set.update(a, b, c)|add a, b, c to the set|
|set.copy( )|copy the set|
|set.remove(n)|remove the item n|
|set.pop()|remove one random item|
|set1.intersection(set2)|return items in both sets|
|set1.difference(set2)|return items in set1 not in set2|

## Dictionnary

A dictionary is a data structure for storing pairs of values with the format key:value.

```
dictionaryName = { key1: val1,  key2: val2,  key3: val3 }
```

|Function|Description|
|---|---|
|d.items( )|return key:value pairs of d|
|d.keys()|return keys of d|
|d.values()|return values of d|
|d.get(key)|return the values with specified key|
|d.pop(key)|remove key and return its value|
|d.clear()|remove all items of d|
|d.copy()|copy all items of d|
|d.setdefault(k,v)|set key:value to (k,v)|

