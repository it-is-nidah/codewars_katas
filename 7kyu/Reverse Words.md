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
Solution 2:

```python

def reverse_words(str):
  newStr = []
  for i in str.split(' '):
      newStr.append(i[::-1])
  return ' '.join(newStr)
print(reverse_words("leon is leoo"))
```
