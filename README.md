## Hey 👋, This is Evans Pauliuts
<p align=left> <img src=https://komarev.com/ghpvc/?username=EvansPauliuts alt=EvansPauliuts /> </p>

```python
from typing import List, Dict
from dataclasses import dataclass, field


def get_code() -> Dict[str, List[str]]:
    languages: dict = {
        'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS'],
        'backend': ['Python', 'Flask', 'Django', 'Django REST framework', 'FastApi'],
        'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB'],
        'devops': ['Docker', 'Nginx', 'Jenkins', 'GitHub Actions', 'AWS', 'Heroku'],
        'tools': ['GIT', 'GitHub', 'GitLab', 'Pandas', 'Jupyter notebook', 'SQLAlchemy', 'Redis'],
        'editor': ['Pycharm', 'Vim'],
        'architecture': ['SPA', 'MVC', 'Serverless', 'Microservices']
    }
    return languages


@dataclass
class EngineerDeveloper:
    name: str = 'Evans Pauliuts'
    role: str = 'Software Engineer'
    code: Dict[str, List[str]] = field(default_factory=get_code)

    def say_hi(self) -> str:
        print('Thanks for dropping by, hope you find some of my work interesting.')
        
        
me: EngineerDeveloper = EngineerDeveloper()
me.say_hi()
```

<!-- [![Github stats](https://github-readme-stats.vercel.app/api?username=EvansPauliuts&show_icons=true&include_all_commits=true)](https://github.com/EvansPauliuts/github-readme-stats) -->
<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EvansPauliuts&layout=compact)](https://github.com/EvansPauliuts/github-readme-stats) -->
