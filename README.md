#in Programmer class
class Employee:
    company = "Google"
    def showDetails(self):
        print("This is an employee")

class Programmer(Employee):
    language = "python"
    company = "youtube"

    def getlanguage(self):
        print(f"The language is {self.language}")
    def showDetails(self):
        print("This is an employee")

e = Employee()
e.showDetails()
#print(e.company)
p = Programmer()
p.showDetails()
print(p.company)

#singl inheritance
class Employee:
    company = "Google"
    def showDetails(self):
        print("This is an employee")

class Programmer(Employee):
    language = "python"
    company = "youtube"

    def getlanguage(self):
        print(f"The language is {self.language}")
    def showDetails(self):
        print("This is an employee")

e = Employee()
e.showDetails()
#print(e.company)
p = Programmer()
p.showDetails()
print(p.company)

#multpal inheritance
class freelancer:
    company = "fiverr"
    level = 0

    def upgradelevel(self):
        self.level = self.level + 1 

class employee:
    company = "visa"
    level = 120

class programmer(employee, freelancer):
    name = "Sunil"

p = programmer()
p.upgradelevel()
print(p.company)

#muletilevel inheritance
class Person:
    country = "India"
    def takeBreath(self):
        print("I am breathing...")

class Employee(Person):
    company = "Honda"
    def getSalary(self):
        print(f"Salary is {self.salary}")

    def takeBreath(self):
        print("I am Employee so I am luckily breathing...")

class Programmer(Employee):
    company = "fiver"
    def getSalary(self):
        print(f"No salary to programmers")

    def takeBreath(self):
        print("I am a Programmer so I am Breathing++..")

p = Person()
p.takeBreath()
e = Employee()
e.takeBreath()
#e.takeBreath()
print(e.company)
pr = Programmer()
pr.takeBreath()
print(pr.country)

#Super method
class Person:
    country = "India"
    def takeBreath(self):
        print("I am breathing...")

class Employee(Person):
    company = "Honda"
    def getSalary(self):
        print(f"Salary is {self.salary}")

    def takeBreath(self):
        super().takeBreath()
        print("I am Employee so I am luckily breathing...")

class Programmer(Employee):
    company = "fiver"
    def getSalary(self):
        print(f"No salary to programmers")

    def takeBreath(self):
        print("I am a Programmer so I am Breathing++..")

p = Person()
p.takeBreath()

e = Employee()
e.takeBreath()

pr = Programmer()
pr.takeBreath()

#constructor the base class

class Person:
    country = "India"

    def __init__(self):
        print("Initializing Person...\n")

    def takeBreath(self):
        print("I am breathing...")

class Employee(Person):
    company = "Honda"

    def __init__(self):
        super().__init__()
        print("Initializing Employee...\n")
        
    def getSalary(self):
        print(f"Salary is {self.salary}")

    def takeBreath(self):
        super().takeBreath()
        print("I am Employee so I am luckily breathing...")

class Programmer(Employee):
    company = "fiver"

    def __init__(self):
        super().__init__()
        print("Initializing Programmer...\n")
        
    def getSalary(self):
        print(f"No salary to programmers")

    def takeBreath(self):
        print("I am a Programmer so I am Breathing++..")

#p = Person()
#p.takeBreath()

#e = Employee()
#e.takeBreath()

pr = Programmer()
#pr.takeBreath()

#class method
