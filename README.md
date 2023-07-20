### Hi, I'm Nibaldo '''<img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> '''

<h3>Tools</h3>
<img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=niba291&langs_count=10&theme=tokyonight&layout=compact"/>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/python-FFFF00.svg?style=for-the-badge&logo=python&logoColor=0768a8&labelColor=ffffff" alt="python"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/c%23-4B0082.svg?style=for-the-badge&logo=c-sharp&logoColor=4B0082&labelColor=ffffff" alt="csharp"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/PHP-6566ba.svg?style=for-the-badge&logo=php&logoColor=6566ba&labelColor=ffffff" alt="javascript"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/java-FC0000.svg?style=for-the-badge&logo=oracle&logoColor=FC0000&labelColor=ffffff" alt="java"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/Node-43853D.svg?style=for-the-badge&logo=node.js&logoColor=43853D&labelColor=ffffff" alt="node"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/JS-f5f542.svg?style=for-the-badge&logo=javascript&logoColor=f5f542&labelColor=ffffff" alt="javascript"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/react-61DAFB.svg?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=ffffff" alt="react"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/jquery-0868AC.svg?style=for-the-badge&logo=jquery&logoColor=0868AC&labelColor=ffffff" alt="django"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/Flask-000000.svg?style=for-the-badge&logo=Flask&logoColor=000000&labelColor=ffffff" alt="flask"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/Laravel-FF2D20.svg?style=for-the-badge&logo=Laravel&logoColor=FF2D20&labelColor=ffffff" alt="laravel"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/Bootstrap-563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=563D7C&labelColor=ffffff" alt="bootstrap"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/mysql-3aabe8.svg?style=for-the-badge&logo=mysql&logoColor=3aabe8&labelColor=ffffff" alt="mysql"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/MariaDB-003545.svg?style=for-the-badge&logo=mariadb&logoColor=003545&labelColor=ffffff" alt="mariadb"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/MongoDB-4EA94B.svg?style=for-the-badge&logo=mongodb&logoColor=4EA94B&labelColor=ffffff" alt="mongodb"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/SQL_Server-CC2927.svg?style=for-the-badge&logo=microsoft-sql-server&logoColor=CC2927&labelColor=ffffff" alt="sqlserver"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/sqlite-1daede.svg?style=for-the-badge&logo=sqlite&logoColor=1daede&labelColor=ffffff" alt="sqlite"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/git-F05032.svg?style=for-the-badge&logo=git&logoColor=F05032&labelColor=ffffff" alt="git"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/github-black.svg?style=for-the-badge&logo=github&logoColor=black&labelColor=ffffff" alt="github"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/Linux-000000.svg?style=for-the-badge&logo=linux&logoColor=000000&labelColor=ffffff" alt="linux"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/windows-3795fa.svg?style=for-the-badge&logo=windows&logoColor=3795fa&labelColor=ffffff" alt="windows"></a>
<a href="https://github.com/niba291"><img src="https://img.shields.io/badge/vscode-blue.svg?style=for-the-badge&logo=visual-studio-code&labelColor=ffffff&logoColor=blue" alt="vscode"></a>
<hr>

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
    languages   : Tuple[str, ...] = ("Python", "PHP", "Java", "C#", "Node", "JavaScript")
    databases   : Tuple[str, ...] = ("MySQL", "MariaDB", "SQL Server", "MongoDB", "NoSql", "SqlLite")
    misc        : Tuple[str, ...] = ("GIT", "React", "Jquery", "DJango", "Flask", "Bootstrap")

class Languages(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Spanish Native", "English B1-B2")
```
