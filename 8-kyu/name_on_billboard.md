## Name on billboard

You can print your name on a billboard ad. Find out how much it will cost you. Each letter has a default price of £30, but that can be different if you are given 2 parameters instead of 1.

You can not use multiplier "*" operator.

If your name would be Jeong-Ho Aristotelis, ad would cost £600. 20 leters * 30 = 600 (Space counts as a letter).

### Solution

```python
def billboard(name, price=30):
    return sum(price for i in name)
```

- Python 3.8

[See on codewars.com](https://www.codewars.com/kata/570e8ec4127ad143660001fd/train/python)

---

@lenargasimov 🥷 2021