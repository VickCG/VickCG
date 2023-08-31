### Hi there 👋

```
#!/usr/bin/python
# -*- coding: utf-8 -*-


class AboutMe:
    def __init__(self):
        self.name = "VickCG"
        self.location = "Hanoi"
        self.technologies = {
            "Back_end": {
                "Python": ["Fast API", "Django"]
            },
            "Devops": ["AWS", "GCP", "Digital Ocean", "Docker🐳", "CI/CD"],
            "Databases": ["Mongo", "MySql", "Postgres", "Dynamodb", "Redis"],
            "Misc": ["Firebase", "Elasticsearch"],
            "Testing": ["Jest", "Cypress", "Pytest"]
        }

    def say_hi(self):
        print("Hi folks, I'm a programming geek, right now I'm working hard to build some interesting things.
               I love connecting with everyone so if you want to say hi, I'll be happy to meet you more! 😊 ")

me = AboutMe()
me.say_hi()
```

