### Write a function that takes an array of numbers and returns the sum of the numbers. 

The numbers can be negative or non-integer. If the array does not contain any numbers then you should return 0.

#### Examples

Input: [1, 5.2, 4, 0, -1]

Output: 9.2

Input: []

Output: 0

Input: [-2.398]
Output: -2.398

#### Assumptions

1. You can assume that you are only given numbers.
2. You cannot assume the size of the array.
3. You can assume that you do get an array and if the array is empty, return 0.

#### Solution 1
```python
def sum_array(a):
    if len(a) == 0:
        return 0
    sum = 0
    for index in a:
        sum += index
    return sum
```
#### Solution 2

```python
def sum_array(a):
  return sum(a)
```
