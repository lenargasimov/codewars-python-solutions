## Grasshopper - Summation

Write a program that finds the summation of every number from 1 to num. The number will always be a positive integer greater than 0.

For example,

```python
summation(2) -> 3
1 + 2

summation(8) -> 36
1 + 2 + 3 + 4 + 5 + 6 + 7 + 8
```

---

### Solution

```python
def summation(num):
    return sum([i for i in range(1,num + 1)])
```
- Python 3.8

[See on codewars.com](https://www.codewars.com/kata/55d24f55d7dd296eb9000030/train/python)

---

@lenargasimov 🥷 2021

    
