### Hi there š

š­ Iām currently working on Something Really Cool \
š± Iām currently learning NextJs, Docker ,Pytorch


``` python
from typing import List

__author__ = "Eswar Divi"
__email__ = "eswar.divi.902@gmail.com"
__description__ = (
    "š Pythonista | š Open-source enthusiastic | š¬ Deep Learning | š” Innovator"
)
__location__ = "š Anytown, SomeWhere"
__github__ = "https://github.com/EswarDivi"


class Who:
    def __init__(self):
        self.author = __author__
        self.email = __email__
        self.description = __description__
        self.location = __location__
        self.github = __github__
        self.interests = [
            "š Data science",
            "š¤ Machine learning",
            "šØ Creative coding",
            "š® Game development",
        ]
        self.skills = [
            "š Python",
            "ā Java",
            "š„ Firebase",
            "š Scala",
            "š PostgreSQL",
            "š MongoDB",
        ]
    def get_interests(self) -> str:
        return " | ".join(self.interests)

    def get_skills(self) -> str:
        return " | ".join(self.skills)

    def __repr__(self):
        return f"<h1>{self.author}</h1><p>{self.description}</p><p>{self.location}</p><p>Interests: {self.get_interests()}</p><p>Skills: {self.get_skills()}</p><a href='{self.github}' target='_blank'>Check out my code on GitHub</a>"


Who()

```

<h1>Eswar Divi</h1><p>š Pythonista | š Open-source evangelist | š¬ Deep Learning | š” Innovator</p><p>š Anytown, SomeWhere</p><p>Interests: š Data science | š¤ Machine learning | šØ Creative coding | š® Game development</p><p>Skills: š Python | ā Java | š„ Firebase | š Scala | š PostgreSQL | š MongoDB</p><a href='https://github.com/EswarDivi' target='_blank'>Check out my code on GitHub</a>

