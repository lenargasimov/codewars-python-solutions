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

[See on CodeWars.com](https://www.codewars.com/kata/50654ddff44f800200000007/train/python)

---

## 👨‍💻 Author

<img style="border-radius: 50%" src="https://github.com/lenargasimov.png" width="100px;" alt=""/>
<br>
  
<p>
<b>Lenar Gasimov</b><br>Python developer | Python, Django, Flask.</p>
    
[![Website](https://img.shields.io/badge/Website/Blog-black?&style=for-the-badge&logo=website&logoColor=white)](https://lenargasimov.dev)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/lenargasimov)
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lenargasimov)
[![Yahoo](https://img.shields.io/badge/Yahoo-720e9e?style=for-the-badge&logo=yahoo&logoColor=white)](mailto:lenargasimov@yahoo.com)
[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/lenargasimov)
