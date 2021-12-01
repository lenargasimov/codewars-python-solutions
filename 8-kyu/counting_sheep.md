## Counting sheep...

Consider an array/list of sheep where some sheep may be missing from their place. We need a function that counts the number of sheep present in the array (true means present).

For example,

```python
[True,  True,  True,  False,
  True,  True,  True,  True ,
  True,  False, True,  False,
  True,  False, False, True ,
  True,  True,  True,  True ,
  False, False, True,  True]
```
The correct answer would be 17.

Hint: Don't forget to check for bad values like null/undefined

---

### Solution

```python
def count_sheeps(sheep):
    return sheep.count(True)
```
- Python 3.8

[See on codewars.com](https://www.codewars.com/kata/54edbc7200b811e956000556/train/python)

---

@lenargasimov 🥷 2021