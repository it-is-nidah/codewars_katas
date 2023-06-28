## Beginner Series #2 Clock

Clock shows h hours, m minutes and s seconds after midnight.

Your task is to write a function which returns the time since midnight in milliseconds.

Example:
h = 0
m = 1
s = 1

result = 61000
Input constraints:

0 <= h <= 23
0 <= m <= 59
0 <= s <= 59

## Solution 
```python
def past(h, m, s):
    ms = 1000
    return h*3600*ms + m*60*ms + s*ms
```

## Solution:

```python
def past(h, m, s):
    hms = h * 3600000
    mms = m * 60000
    sms = s * 1000
    return (hms + mms + sms)

past(1,1,1)
```
