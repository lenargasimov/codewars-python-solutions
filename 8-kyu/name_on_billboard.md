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

[See on CodeWars.com](https://www.codewars.com/kata/570e8ec4127ad143660001fd/train/python)

---

## Author

<img style="border-radius: 50%" src="https://github.com/lenargasimov.png" width="100px;" alt=""/>
<br>
  
<p>
<b>Lenar Gasimov</b><br>Python developer | Python, Django, Flask.</p>
    
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/lenargasimov)
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lenargasimov)
[![DuckDuckGo](https://img.shields.io/badge/email-DE5833?style=for-the-badge&logo=DuckDuckGo&logoColor=white)](mailto:lenargasimov@duck.com)
