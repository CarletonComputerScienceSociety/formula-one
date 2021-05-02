# Sets

*Sets are unordered collection and unindexed (cannot be accessed directly) stored in curly brackets "*{ }"

The following code assigns a sample set to a variable, which can then be used to manipulate. 

```python
example_set = {1, 'a', True}
```

### Access

```python
for x in example_set:
     item = x
```

As part of access, you can check if a certain item is in the set, as shown below. 

### Check if in list -> Returns True or False
```python
check = 1 in example_set
```

### Add

### Add Item
```python
example_set.add ('b')
```

### Add two sets ~ update() can be used to any iterable objects
```python
example_set2 = {2, 'c', False}
example_set.update (example_set2)
```

### Remove

```python
example_set.remove ('a')
```
### If 'a' does not exist, then discard() does not raise an error
```python
example_set.discard ('a')
```