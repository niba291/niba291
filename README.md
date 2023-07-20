### Hi there 👋

```python

from dataclasses import dataclass
from typing import Tuple

class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Nibaldo Chavez"
    designation : str = "Full Stack Programmer"
    company     : str = "Chile"
    page        : str = "ddsolutions.cl"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "PHP", "Java", "C#", "Node")
    databases   : Tuple[str, ...] = ("MySQL", "SQL Server", "MongoDB", "NoSql")
    misc        : Tuple[str, ...] = ("GIT", "React", "Jquery")

class Social(metaclass=Meta):
    twitter     : str = "rednafi"
    linkedin    : str = "redowan"
```
