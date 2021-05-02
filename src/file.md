# Files

The following code shows how to read, modify and close the files with their particular order. 

### Always open the file with read, append or write, modify, then close the file.
```python
example_file = "file-name.txt"
```

### Opens file and "r" read (error if does not exist), "a" append and "w" write
```python
infile = open(example_file, "r")
```

### Returns one line, if called twice, it reads first two lines of the file
```python
infile.readline() 
infile.close() # closes the file
```