ATM machines allow 4 or 6 digit PIN codes and PIN codes cannot contain anything but exactly 4 digits or exactly 6 digits.

If the function is passed a valid PIN string, return true, else return false.

Examples (Input --> Output)

"1234"   -->  true

"12345"  -->  false

"a234"   -->  false

Solution;
```python

def validate_pin(pin):
    r = len(pin)
    return pin.isdigit() if r == 4 or r == 6 else False
```

Solution 2;

```python
def validate_pin(pin):
    return len(pin) in (4, 6) and pin.isdigit()
```
