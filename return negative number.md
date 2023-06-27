#### In this simple assignment you are given a number and have to make it negative. But maybe the number is already negative?

Examples

make_negative(1);  # return -1

make_negative(-5); # return -5

make_negative(0);  # return 0

#### Notes
The number can be negative already, in which case no change is required.
Zero (0) is not checked for any specific sign. Negative zeros make no mathematical sense.

#### Solution:
```python3
def make_negative( number ):
    return -abs(number)
```


https://stackoverflow.com/questions/64445167/how-to-convert-positive-numbers-to-negative-in-python


The abs (absolute value) function returns the positive value in case of negative numbers. 
So we are negating it ( -abs) so that the -abs returns the negative in case of positive numbers. 
This will have no effect on the negative numbers.

#### another solution;

This follows the tenary operator which i like to remember as WTF:
W - *What* ->statement or condition. return -number (make number negative)
T - *True* -> if number > 0 (if it is a positive number)
F - *False* -> else number ( if it is a negative number, return it as is)

```python
def make_negative(number):
    return -number if number > 0 else number
```
