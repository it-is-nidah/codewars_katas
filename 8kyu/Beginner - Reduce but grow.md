Given a non-empty array of integers, return the result of multiplying the values together in order.

Example:

[1, 2, 3, 4] => 1 * 2 * 3 * 4 = 24

```python3

def grow(arr):
    res = 1
    for r in arr: 
        res = res * r
    return res
```
