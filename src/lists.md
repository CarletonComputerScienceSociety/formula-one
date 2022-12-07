# Lists

Lists are ordered collections with possible duplicates stored in square brackets " [ ] "

The following code assigns a list to a variable, which will then be used to manipulate.

```python
example_list = ['a', 1, True, 4, 6, 'b']
```

## Access

```python
example_list [-1] # Backwards accessing
example_list [2:5] # Third, Fourth and Fifth item 
example_list [2:] # Access from third time to the end of the list
```

## Change

```python
example_list [0] = 'c' # It is not 'a' anymore, it is 'c' for the first element
example_list [1:3] = ['x', 3] # The second and third item are now 'x' and 3
example_list [1:3] = ['r'] # Replaces the range of items with just one item 'r'
```

## Add/Extend

## Without replacing, 'b' slides in between the the second and third item
```python
example_list.insert (2, 'b')
```

## Adds 'q' to the end of the list
```python
example_list.append ('q')
```

Extend -> extend () works for any iterable objects e.g. tuples, sets, dictionaries, etc.

```python
example_list2 = ['l', 10]
```
## Adds the entire example_list2 list to the end of the list as elements
```python
example_list.extend (example_list2)
```

## Remove

```python
example_list.remove ('a') # Removes the specific item
`example_list.pop(1) # Removes the specific item at that index
`del example_list[2] # Removes the specific item at that index
`example_list.clear() # Keeps the list empty by removing all elements
```

## Looping

```python
# For-Loop for each item
for i in range (len(example_list)):
     item = example_list[1]

# While Looping
i = 0
while i < len(example_list):
     item = example_list[i]
     i += 1
```