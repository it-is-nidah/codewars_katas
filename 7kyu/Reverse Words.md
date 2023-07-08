Complete the function that accepts a string parameter, and reverses each word in the string. All spaces in the string should be retained.

Examples

"This is an example!" ==> "sihT si na !elpmaxe"

"double  spaces"      ==> "elbuod  secaps"

Solution:

```python

def reverse_words(text):
    
    return(' '.join(t[::-1] for t in text.split(' ')))

print(reverse_words('Leo\'s world is Kericho, Kenya'))

```
