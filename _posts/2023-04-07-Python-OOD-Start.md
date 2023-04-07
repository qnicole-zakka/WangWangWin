
#title: "Python-OOD-Start"**
#date: 2023-04-07


**Super()** function inside of **__init__**  

```python
class Animal:
    def __init__(self, name):
        self.name = name
        print("Animal created")

# Class Dog inherits class Animal
class Dog(Animal):
    def __init__(self, name):
        super().__init__(name) # inherits the __init__ function in parent
        print("Dog created")

my_dog = Dog("Fido")

```
