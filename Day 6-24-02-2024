#multilevel inheritance
'''
class vehicle:
    def __init__(self,fuel):
        self.fuel=fuel
    def display3(self):
        print(self.fuel)
class motor(vehicle):
    def __init__(self,cc,fuel):
        self.cc=cc
        self.fuel=fuel
        super().__init__(fuel)
    def display2(self):
        print(self.cc)
        print(self.fuel)
class car(motor):
    def __init__(self,brand,cc,fuel):
        self.brand=brand
        self.cc=cc
        self.fuel=fuel
        super().__init__(cc,fuel)
    def display1(self):
        print(self.brand)
        print(self.cc)
        print(self.fuel)
v1=car("bmw","300cc","petrol")
v1.display1()
v1.display2()
v1.display3()
'''
#multiple inheritance
''''
class vehicle:
    def __init__(self,cc,fuel):
        self.cc=cc
        self.fuel=fuel
    def display3(self):
        print(self.cc)
        print(self.fuel)
class motor:
    def display2(self):
        pass
class car(vehicle,motor):
    def __init__(self,brand,cc,fuel):
        self.brand=brand
        self.cc=cc
        self.fuel=fuel
        super().__init__(cc,fuel)
    def display1(self):
        print(self.brand)
        print(self.cc)
        print(self.fuel)
v1=car("bmw","300cc","petrol")
v1.display1()
v1.display2()
v1.display3()
'''
#hierarchial inheritance
'''
from abc import ABC,abstractmethod
class shape(ABC):
    @abstractmethod
    def area(self):
        pass
class rect(shape):
    def __init__(self,l,b):
        self.l=l
        self.b=b 
    def area(self):
        print(self.l*self.b)
class square(shape):
    def __init__(self,s):
        self.s=s
    def area(self):
        print(self.s*self.s)
v1=rect(100,200)
v1.area()
v2=square(200)
v2.area()
'''
#exception handling
'''
try:
    c=10/0
except:
    print("error occured")
else:
    print(c)
finally:
    print("hello")
'''
#2
'''
try:
    c=10/0
except:
    print("error occured")
else:
    print(c)
'''
#3
'''
try:
    c=10/2
except:
    print("error occured")
else:
    print(c)
finally:
    print("hello")
    '''
#4
'''
try:
    a=int(input())
    c=a/0
except ZeroDivisionError:
    print("division error")
except:
    print("error occured")
else:
    print(c)
finally:
    print("hello")
    '''
#5
'''
try:
    a="abc"
    c=a/0
except ZeroDivisionError:
    print("division error")
except:
    print("error occured")
else:
    print(c)
'''
#6

try:
    a=int(input())
    c=a/0
except ZeroDivisionError:
    print("division error")
except Exception as a:
    print(a)
else:
    print(c)
finally:
    print("good to see you srinu")


#7
'''
a=int(input())
print(a/0)
'''
