## Reversed Words

Complete the solution so that it reverses all of the words within the string passed in.

### Example:

```
"The greatest victory is that which requires no battle" --> "battle no requires which that is victory greatest The"
```

---

### Solution:

```python
def reverse_words(s):
    return ' '.join(reversed(s.split()))
```

- Python 3.8

[See on codewars.com](https://www.codewars.com/kata/51c8991dee245d7ddf00000e/train/python)

---

@lenargasimov 🥷 2021

