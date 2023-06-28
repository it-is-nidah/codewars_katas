We need a function that can transform a number (integer) into a string.


Examples (input --> output):
123  --> "123"
999  --> "999"
-100 --> "-100"

Given code:

```python
def number_to_string(num):
    # Return a string of the number here!
 ```
 
 Solution 1:
 
 ```python
 def number_to_string(num):
    return str(num)
  ```
  
 Solution 2;
 
 ```python
 def number_to_string(num):
    try:
        return str(num)
    except:
        return None
  ```      
