<h1>Week 3 - Journal</h1>

<h3>What</h3>

This week I learned about the data structures of Python and how important they are. Python has four key data structures that enable Python to store and manipulate data. 

<h4>Text (str object)</h4>

Python uses text to store string plain text as Unicode characters. This enables Python to manipulate the data, allowing us to change text.

For example:

```python
s = "TEXT"
print(s[-1])
```

```output: "T"```

From the example above, the text data structure allows us to store a list of characters easily and extract characters efficiently with slices. This data structure allows Python to store user input


<h4>Tuple</h4>

Python uses tuples to store multiple values in a single object. This enables python to have multiple strings in one variable.

For example:

```python
a = ("apple", "banana", "cherry")
print(a)
```

```output: ('apple', 'banana', 'cherry')```

From this example above, the tuple data structure allows us to store multiple values easily and efficiently in a variable. Tuples items are ordered, unchangeable and allows duplicate values. The items can also be indexed, but no values can be added, remove or modified.

<h4>List</h4>

Python uses lists to store multiple values inside a single object. Although unlike Tuples the values in a list can be changed, removed, added, duplicated, indexed and ordered.

For example:

```python
a = ["apple", "banana", "cherry"]
print(a)
```

```output: ['apple', 'banana', 'cherry']```

<h4>Dictionary</h4>  

Python uses dictionaries to store values as key:value pairs. 

For example:

```python
a = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(a)
```

```output: {'brand': 'Ford', 'model': 'Mustang', 'year': 1964}```

This example shows values represented by a key. The values can be targeted using the key, and the key can be targeted by values. Dictionaries are really good for storing objects.

<h4>Set</h4>

Python uses set to store multiple values inside an object variable.

For example:

```python
thisset = {"apple", "banana", "cherry"}
print(thisset)```
```

```output: {'apple', 'banana', 'cherry'} ```

When items are set, they are unordered, unchangeable and cannot contain duplicated values. Sets cannot contains values that are the same as exitsing values.

<h4>Range</h4>

Python uses range to return a sequence of numbers by counting. This sequence can have the numbers correlate to an action or represent a value.

For example:

```python
x = range(6)
for n in x:
 print(n)
```

```output: 0,1,2,3,4,5```

Range be default will start at 0, and will count, printing each number, one at a time.



Overall data structures are important to learn about as it makes me more insightful and knowledgeable about Python. From leaning about the different data structures I know have a better understanding of how to manipulate data.

<h3>References</h3>

*Python dictionaries*. (n.d.). W3Schools Online Web Tutorials. Retrieved August 10, 2021, from https://www.w3schools.com/python/python_dictionaries.asp

*Python lists*. (n.d.). W3Schools Online Web Tutorials. Retrieved August 10, 2021, from https://www.w3schools.com/python/python_lists.asp

Python, R. (2020, August 26). *Common Python data structures (Guide) – Real Python*. Python Tutorials – Real Python. Retrieved August 10, 2021, from https://realpython.com/python-data-structures/

*Python range() function*. (n.d.). W3Schools Online Web Tutorials. Retrieved August 10, 2021, from https://www.w3schools.com/python/ref_func_range.asp

*Python sets*. (n.d.). W3Schools Online Web Tutorials. Retrieved August 10, 2021, from https://www.w3schools.com/python/python_sets.asp

*Python Tuples*. (n.d.). W3Schools Online Web Tutorials. Retrieved August 10, 2021, from https://www.w3schools.com/python/python_tuples.asp