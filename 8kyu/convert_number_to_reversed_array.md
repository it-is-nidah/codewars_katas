### Given a random non-negative number, you have to return the digits of this number within an array in reversed order.

For example; 
      4393807 => [7,0,8,3,9,3,4]
      0 => [0]
      425 => [5,2,4]
      
  Given Code: 

```python
  def digitize(n):
    return
  ```

##   Solution 1
  ```python3
    def digitize(n):
       return [int(i) for i in str(n)[::-1]]
    print(digitize(58938))
```

## Solution 2

```python
def digitize(n):
# initialize an empty array
    arr = [] 
      # convert the number n to a string and iterate through it
    for number in str(n): 
          # inserts each number in the first position of our array; so this will insert the every new value returned to the first position, hence reversing the order of n
        arr.insert(0, int(number)) 
    return num_array 

print(digitize(69254))
```
