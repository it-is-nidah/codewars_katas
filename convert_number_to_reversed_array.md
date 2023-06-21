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

##   My answer
  ```python3
    def digitize(n):
       return [int(i) for i in str(n)[::-1]]
    print(digitize(58938))
```
