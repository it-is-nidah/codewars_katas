Implement a function that adds two numbers together and returns their sum in binary. The conversion can be done before, or after the addition.

The binary number returned should be a string.

Examples:(Input1, Input2 --> Output (explanation)))

1, 1 --> "10" (1 + 1 = 2 in decimal or 10 in binary)
5, 9 --> "1110" (5 + 9 = 14 in decimal or 1110 in binary)

Solution:

```python
def add_binary(a,b):
    sum = a+b
    return format(sum, "0b")
    
# The general format is
# format(<the_integer>, "<0><width_of_string><format_specifier>")
```

Solution Simplified;

```python
def add_binary(a,b):
    return format(a+b, "0b")
```
