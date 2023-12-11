Nathan loves cycling.

Because Nathan knows it is important to stay hydrated, he drinks 0.5 litres of water per hour of cycling.

You get given the time in hours and you need to return the number of litres Nathan will drink, rounded to the smallest value.

For example:

time = 3 ----> litres = 1

time = 6.7---> litres = 3

time = 11.8--> litres = 5


Solution 1
```python
import math # this is needed in order to use math.floor() function

def litres(time):
    l = math.floor(time * 0.5)
    return l
```

Solution 2
```python
def litres(time):
    return int(time*0.5)
```

Solution 3 using the < // > floor division
```python
def litres(time):
    return time // 2
```
