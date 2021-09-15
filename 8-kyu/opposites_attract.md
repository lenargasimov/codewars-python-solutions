## Opposites Attract

Timmy & Sarah think they are in love, but around where they live, they will only know once they pick a flower each. If one of the flowers has an even number of petals and the other has an odd number of petals it means they are in love.

Write a function that will take the number of petals of each flower and return true if they are in love and false if they aren't.

### Solution

```python
def lovefunc( flower1, flower2 ):
    if flower1 % 2 == 0 and flower2 % 2 != 0 or flower1 % 2 != 0 and flower2 % 2 == 0:
        return True
    else: 
        return False
```

- Python 3.8

[See on CodeWars.com](https://www.codewars.com/kata/555086d53eac039a2a000083/train/python)

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
