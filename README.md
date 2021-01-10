<h3>Hi there! 👋</h3>

## My stack 👨‍💻	<sub>From most experience to least</sub>

![Python](https://img.shields.io/badge/-Python-%230075a8?logo=python&logoColor=white&style=flat-square) ![JavaScript](https://img.shields.io/badge/-JavaScript-%23e9d54c?logo=javascript&logoColor=white&style=flat-square) ![HTML](https://img.shields.io/badge/-HTML-%23de4b25?logo=html5&logoColor=white&style=flat-square) ![CSS](https://img.shields.io/badge/-CSS-%230174b8?logo=css3&logoColor=white&style=flat-square) ![Git](https://img.shields.io/badge/-Git-%23ea4f32?logo=git&logoColor=white&style=flat-square) ![Nim](https://img.shields.io/badge/-Nim-%23e9c241?logo=nim&logoColor=white&style=flat-square)

* Using JS for most of my projects
* Learning Nim
* Diving into Web/Android reverse engineering

## Contact me 💭
- <a href="mailto:ltmtp32@gmail.com">📩 E-mail (prefered): `ltmtp32@gmail.com`</a>

## Stats 📊
<img src="https://gpvc.arturio.dev/ltmtp32-dev" align="center" />
<img src="https://github-readme-stats.vercel.app/api?username=ltmtp32-dev&show_icons=true&count_private=true">

<!-- Zero width character is used to put extra blank lines before and after code -->

<h4>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple[str, ...] = ("Python", "NodeJS", "Rust")
    databases   : tuple[str, ...] = ("MongoDB", "Redis", "PostgreSQL")
    misc        : tuple[str, ...] = ("k8s", "ZMQ")
    ongoing     : tuple[str, ...] = ("Django", "Typescript")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
​
```
</h4>

