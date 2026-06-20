class Azhagumuthu:
    def __init__(self):
        self.name = "Azhagumuthu R"
        self.location = "Coimbatore, Tamil Nadu, India"
        self.degree = "B.E. in ECE, Akshaya College of Engineering & Tech (2025)"
        self.role = "Aspiring Full Stack Python Developer"

        self.stack = [
            "Python", "Django", "Flask",
            "JavaScript", "React", "Angular",
            "HTML", "CSS", "Bootstrap", "jQuery",
            "MySQL", "SQL"
        ]

        self.currently_learning = [
            "Java (Spring Boot)",
            "Advanced Data Structures",
            "System Design Basics"
        ]

        self.fun_fact = "I once built a home automation system controlled by brainwaves (EEG)!"

    def motto(self):
        return "Keep building, keep debugging, keep learning."


me = Azhagumuthu()
print(me.motto())
