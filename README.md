### Hi there 👋

```
#!/usr/bin/python
# -*- coding: utf-8 -*-


class MySelf:
    def __init__(self):
        self.name = "VickCG"
        self.role = "Free guy at home"
        self.location = "Hanoi"
        self.technologies = {
            "front_end": ["Angular", "React"],
            "back_end": {
                "nodejs": ["NestJS", "Express", "AdonisJS"],
                "python": ["Fast API", "Django"]
            },
            "devops": ["AWS", "GCP", "Docker🐳", "CI/CD"],
            "databases": ["mongo", "MySql", "postgres", "dynamodb", "redis"],
            "misc": ["Firebase", "Elasticsearch"]
        }

    def say_hi(self):
        print("Hi folks, I'm a programming geek, right now I'm working hard to build some interesting things.
               I love connecting with different people so if you want to say hi, I'll be happy to meet you more! 😊 ")

me = MySelf()
me.say_hi()
```

