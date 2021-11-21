## Return Negative

In this simple assignment you are given a number and have to make it negative. But maybe the number is already negative?

Example:

```python
make_negative(1);  # return -1
make_negative(-5); # return -5
make_negative(0);  # return 0
```

Notes:

- The number can be negative already, in which case no change is required.
- Zero (0) is not checked for any specific sign. Negative zeros make no mathematical sense.

---

### Solution

```python
def make_negative( number ):
    return -abs(number)
```

- Python 3.8

[See on CodeWars.com](https://www.codewars.com/kata/55685cd7ad70877c23000102/train/python)

---

## Author

<img style="border-radius: 50%" src="https://github.com/lenargasimov.png" width="100px;" alt=""/>
<br>
  
<p>
<b>Lenar Gasimov</b><br>Python developer | Python, Flask.</p>
    
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/lenargasimov)
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lenargasimov)
[![DuckDuckGo](https://img.shields.io/badge/email-DE5833?style=for-the-badge&logo=DuckDuckGo&logoColor=white)](mailto:lenargasimov@duck.com)