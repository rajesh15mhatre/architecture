# Understanding Encapsulation, Inheritance, Polymorphism, Abstraction in OOPs
## Encapsulation
 - Is limiting to change attribute value by using getter and setter methods
 - Or hiding attributes of class
 ```
class parent():
 def __init__(self, name):
  self._name = name
  self.__version = 0.2

 def greet(self):
  print(f"hello {name})

# a getter function
def get_version(self):
    print(f'The sensor version is {self.__version}')

# A setter function
def set_version(self, version):
    self.__version = version
```
- With a single underscore, we defined a private variable, and it should not be accessed directly.  You can still get access to it if you want to.
- With a double underscore, we can see that the attribute __version can not be accessed or modified directly. you would need getter and setter functions to access it internally
## Inheritance:
- We can inheric a class and reuse/override it's methods
- Child class and parent class relation is there
- Syntax
```
class parent():
 def __init__(self, name):
  self.name = name

 def greet(self):
  print(f"hello {name})

class child(parent):
  def bye(self)
    print(f"bye {name}")
```
- we use super() to access parent class
- 
## Polymorphisum
-  polymorphism is the ability of the same object to take multiple forms.
-  BY using method overloading where the method in same class has multiple versions 
  - Python does not support method overloading. We may overload the methods but can only use the latest defined method.
-  By using a method overriding
  -  Modifying parent method in child class

## Absctraction
- Abstraction in general means hiding
- 
