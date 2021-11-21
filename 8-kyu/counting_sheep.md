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

[See on CodeWars.com](https://www.codewars.com/kata/54edbc7200b811e956000556/train/python)

---

## Author

<img style="border-radius: 50%" src="https://github.com/lenargasimov.png" width="100px;" alt=""/>
<br>
  
<p>
<b>Lenar Gasimov</b><br>Python developer | Python, Flask.</p>
    
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/lenargasimov)
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lenargasimov)
[![DuckDuckGo](https://img.shields.io/badge/email-DE5833?style=for-the-badge&logo=DuckDuckGo&logoColor=white)](mailto:lenargasimov@duck.com)