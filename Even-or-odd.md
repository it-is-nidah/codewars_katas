## Create a function that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.

## Solution;

```python
def even_or_odd(number):
    if number % 2 == 0:
        return 'Even'
    else:
        return 'Odd'
    
print(even_or_odd(20))
```

For more information on modulo operator ( % );

https://www.geeksforgeeks.org/what-is-a-modulo-operator-in-python/
