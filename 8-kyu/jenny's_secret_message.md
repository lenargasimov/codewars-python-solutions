## Jenny's secret message

Jenny has written a function that returns a greeting for a user. However, she's in love with Johnny, and would like to greet him slightly different. She added a special case to her function, but she made a mistake.

Can you help her?

### Example:

```python
def greet(name):
    return "Hello, {name}!".format(name=name)
    if name == "Johnny":
        return "Hello, my love!"
```

---

### Solution

```python
def greet(name):
    if name == "Johnny":
        return "Hello, my love!"
    else:
        return f"Hello, {name}!"
```

- Python 3.8

[See on CodeWars.com](https://www.codewars.com/kata/55225023e1be1ec8bc000390/train/python)

---

## 👨‍💻 Author

<img style="border-radius: 50%" src="https://github.com/lenargasimov.png" width="100px;" alt=""/>
<br>
  
<p>
<b>Lenar Gasimov</b><br>Python developer | Python, Flask.</p>
    
[![Website](https://img.shields.io/badge/Website/Blog-black?&style=for-the-badge&logo=website&logoColor=white)](https://lenargasimov.dev)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/lenargasimov)
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lenargasimov)
[![Yahoo](https://img.shields.io/badge/Yahoo-720e9e?style=for-the-badge&logo=yahoo&logoColor=white)](mailto:lenargasimov@yahoo.com)
[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/lenargasimov)
