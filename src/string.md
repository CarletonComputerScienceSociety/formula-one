# Strings

Strings are words/letters that are written using single, double quotation marks. 

The following code assigns a string to a variable, which then can be used to manipulate. 

```python
example_string = "Hello, World!"
```

## Access

```python
example_string [1] # prints the second element in the string, in this case, 'e'
example_string [2:5] # range
example_string [5:] # slice from 6th to end
```

## Modify
## returns string in all uppercase
```python
example_string.upper ()
```

## returns string in all lowercase
```python
example_string.lower ()
```

## removes whitespaces from beginning or at the end
```python
example_string.strip ()
``` 

## repalces the argument 1 with argument 2 in the original string
```python
example_string.replace ("H", "j")
``` 

## returns a list with the words being being split at the given argument
```python
example_string.split (",")
```

An example of multiple commands in one is as follows. 


```python
example_string.strip(string.punctuation).lower().split()
```

## Output:

```python
['hello', ' world!']
```