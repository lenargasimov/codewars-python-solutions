## The Feast of Many Beasts

All of the animals are having a feast! Each animal is bringing one dish. There is just one rule: the dish must start and end with the same letters as the animal's name. For example, the great blue heron is bringing garlic naan and the chickadee is bringing chocolate cake.

Write a function ```feast``` that takes the animal's name and dish as arguments and returns true or false to indicate whether the beast is allowed to bring the dish to the feast.

Assume that ``` beast``` and ```dish``` are always lowercase strings, and that each has at least two letters. ```beast``` and ```dish``` may contain hyphens and spaces, but these will not appear at the beginning or end of the string. They will not contain numerals.

---

### Solution

```python
def feast(beast, dish):
    return beast[0] == dish[0] and beast[-1] == dish[-1]
```

- Python 3.8

[See on CodeWars.com](https://www.codewars.com/kata/5aa736a455f906981800360d/train/python)

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


