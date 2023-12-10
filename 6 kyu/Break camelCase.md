### Complete the solution so that the function will break up camel casing, using a space between words.

Example

"camelCasing"  =>  "camel Casing"

"identifier"   =>  "identifier"

""             =>  ""

Solution:
```python
def solution(s):
    result = ''
    for character in s:
        if character.isupper():
            result += ' ' + character
        else:
            result += character
    return result
```
