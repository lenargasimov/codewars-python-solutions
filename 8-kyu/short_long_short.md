## Short Long Short

Given 2 strings, a and b, return a string of the form short+long+short, with the shorter string on the outside and the longer string on the inside. The strings will not be the same length, but they may be empty ( zero length ).

Hint for R users:

The length of string is not always the same as the number of characters

### For example: (Input1, Input2) --> output

```python
("1", "22") --> "1221"
("22", "1") --> "1221"
```

### Solution

```python
def solution(a, b):
    if len(a) < len(b):
        return a + b + a 
    else:
        return b + a + b
```

- Python 3.8

[See on codewars.com](https://www.codewars.com/kata/50654ddff44f800200000007/train/python)

---

@lenargasimov 🥷 2021