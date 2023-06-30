Complete the method that takes a boolean value and return a "Yes" string for true, or a "No" string for false.

Solution 1

```python
def bool_to_word(boolean):
    return "Yes" if boolean == True else "No"
``````

Solution 2 using tuples

```python
def bool_to_word(boolean):
    return ('No','Yes')[boolean]
```
