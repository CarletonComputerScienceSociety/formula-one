# Tuples

*A tuple is an ordered collection that is unchangeable and is stored in round brackets "* ( ) *"*

The following code assigns a tuple to a variable, which will then be used to manipulate.

```python
example_tuple = (1, 'a', True)
```

### Access

```python
example_tuple [1] # access
```

### Update

```python
tuple_list = list(example_tuple)
tuple_list [1] = 'b'
example_tuple = tuple(tuple_list)
```

### Unpack

```python
(x, y, z) = example_tuple
```