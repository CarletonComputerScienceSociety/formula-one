# Dictionaries

*Dictionaries are arranged in pairs of key:value with no duplicates and can be modified.* 

The code below assigns a dictionary to a variable which then can be called and manipulated. 

```python
example_dict = {"one": 1, "two": False, "three": 3, "four": 4}
```

### Access

There are multiple ways to perform this action, as shown below.

```python
example_dict ["one"] # Gives the value of the key "one"
example_dict.get ("one") # Gives the value of the key "one"
example_dict.keys () # Gives a list of keys
example_dict.values () # Gives a list of values
example_dict.items() # Gives a list of items of (keys, values) as tuples
```

### Change

There are multiple ways to perform this action, as shown below.

```python
example_dict ["two"] = True # Changes the value of key "two" to True
example_dict.update ({"four": False}) # Changes the item with the key "four"
```

### Remove

There are multiple ways to perform this action, as shown below.

```python
example_dict ["five"] = 5 # Adds a new item of "five":5 to the dictionary
example_dict.update ({"six": 6}) # Adds the item to the dictionary
```

### Looping

This is used to access every single item or value/key, depending on the iteration loop. 

```python
for x in example_dict.keys (): # For all keys in the dictionary
     result = x
for y in example_dict.values (): # For all values in the dictionary
     result = x
for x, y in example_dict.items (): # For all items in the dictionary split into x, y
     result = (x, y)
```