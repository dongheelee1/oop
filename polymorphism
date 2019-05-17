
#Polymorphism:

#Example of Method Overriding

class Animal(object):

    def __init__(self, name):
        self.name = name

    def talk(self):
        pass

class Dog(Animal):
    def talk(self):
        print("Woof")

class Cat(Animal):
    def talk(self):
        print("Meow")

cat = Cat('KIT')
cat.talk()

dog = Dog('EDDY')
dog.talk()



#Example of method overloading

def add(typ, *args):
    if typ == 'int':
        result = 0
    if typ == 'str':
        result = ''
    for i in args:
        result += i
    return result

add('int', 1, 2, 3)
add('str', 'i', 'love', 'python')
