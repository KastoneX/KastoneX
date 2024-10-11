## You can contact me via:

<p> <a href="https://t.me/kastonex" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a></p>


``` python
# About me
class Person:
    def __init__(self, name, occupation, education):
        self.name, self.occupation, self.education = name, occupation, education
    def __str__(self): return f"{self.name}, {self.occupation} at {self.education}"
p = Person("Data Scientist")

# What I do
class Interests:
    def __init__(self, i):
        self.i = i

class Projects(Interests):
    def __init__(self, i, p):
        super().__init__(i)
        self.p = p

interests = Interests(["Data analysis", "Machine learning", "Data visualization"])
projects = Projects(interests.i, ["Exploratory data analysis", "Predictive modeling", "Data visualization"])

# What I'm learning
class Learning:
    def __init__(self, l):
        self.l = l

class Blog(Learning):
    def __init__(self, l, b):
        super().__init__(l)
        self.b = b

learning = Learning(["Deep learning", "Big data technologies", "Computer Vision", "Natural language processing"])
blog = Blog(learning.l, "Check out my GitHub for articles and notes on what I'm learning and how I'm using it!")

# Technology stack
class TechnologyStack:
    def __init__(self, programming_languages, machine_learning_libraries, 
    data_analysis_libraries, project_management_tools, code_versioning_tools, interactive_web_libraries):
        self.programming_languages = programming_languages
        self.machine_learning_libraries = machine_learning_libraries
        self.data_analysis_libraries = data_analysis_libraries
        self.project_management_tools = project_management_tools
        self.code_versioning_tools = code_versioning_tools
        self.interactive_web_libraries = interactive_web_libraries
    def __str__(self):
      return f"Programming languages: {', '.join(self.programming_languages)}" \
      f"Machine learning libraries: {', '.join(self.machine_learning_libraries)}" \
      f"Data analysis libraries: {', '.join(self.data_analysis_libraries)}" \
      f"Project management tools: {', '.join(self.project_management_tools)}" \
      f"Code-matching and versioning tools: {', '.join(self.code_versioning_tools)}" \
      f"Libraries for creating interactive web applications: {', '.join(self.interactive_web_libraries)}"

ts = TechnologyStack(
["Python"], 
["scikit-learn", "TensorFlow", "PyTorch"], 
["Pandas", "Numpy", "Matplotlib"], 
["Jupyter Notebook", "Google Colab"], 
["GitHub"], 
["Streamlit"])
```
