#chapter:1
print('hello world')

import os
print(os.listdir())

#chapter:2
#string
a = "Sunil"
print(a)

#integers
b = 345
print(b)

#flooting
c = 45.32
print(c)

#Booleans
d = True
print(d)

#None
e = None
print(e)

#data type
a = "sunil"
b = 345
c = 45.32
d = True
e = None

#variables
print(a)
print(b)
print(c)
print(d)
print(e)

#print the type of variables
print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))

#Arithmetic operators
print("The value of 3+4 is", 3+4)
print("The value of 3-4 is", 3-4)
print("The value of 3*4 is", 3*4)
print("The value of 3/4 is", 3/4)

#Assignment operators
#a = 34

#a += 6
#a -= 6
#a *= 6
a /= 6
print(a)

#Comparison operators
#b = (14>=7)
#b = (14<=7)
#b = (14<7)
#b = (14>7)
#b = (14==7)
b = (14!=7)
print(b)

#logical operators
bool1 = True
bool2 = False
print('The value of bool1 and bool2 is', (bool1 and bool2))
print('The value of bool1 or bool2 is', (bool1 or bool2))
print('The value of not bool2 is', (not bool2))

#type function and typecasting
a = "3534"
a = int(a)
#print(type(a))
#print(a)
print(a + 5)

#input function
a = input('Enter your name')
print(a) 

#chapter 2 prestics set******************************************
# Question:1
a = 5
b = 10
print("two number add", a+b) 

#Question:2
a = 5
>>> b = 27
>>> print(a%b)
5
>>> a = 5
>>> b = 2
>>> print(a/b)
2.5

#Question:3
>>> a = 34
>>> print(a)
34
>>> a = input("Enter anumber")
Enter anumbersunil
>>> type(a)
<class 'str'>
>>>

#Question:4 
a = 34
b = 80
a>b

#Question:5
a = input("Enter first number: ")
b = input("Enter second number: ")
a = int(a)
b = int(b)
avg = (a + b)/2
print("The average of a and b is", avg)

#Question:6

#chapter:3
#concatenating two Strings
a = "Good Morning"
b = " Sunil"
c = a + b
print(c)

#string Slicing
name = "Sunil"
#print(name[3])
#print(name[0:3])
#print(name[:4]) #is same as name[0:4]
print(name[0:]) #is same as name[0:5]

#negative index
name = "Sunil"
c = name[-4: -1]
print(c)

#skip slicing
name = "SunilIsGood"
c = name[0::2]
print(c)

#len() function
story = "Once upon a time"
print(len(story))

#string endswith()
story = "Sunil"
print(story.endswith("nil"))

#string .count()
story = "once upon a time python"
print(story.count("o"))

#string capitalize
story = "name "
print(story.capitalize())

#string .find()
story = "Once upon a time python"
print(story.find("time"))

#string replace
story = "Once upon a time python"
print(story.replace("time", "Onetime"))

#practice set
#Q: 1
name = input("Enter your name")
print("Good Afternoon, " + name)

#Q: 2
letter = '''Dear <|NAME|>,
Greeting from ABC coding house.
I am happy to your selection.
Thanks and regards,
Sunil
Date: <|DATE|>'''
name = input("Enter Your Name\n")
date = input("Enter Date\n")
letter = letter.replace("<|NAME|>", name)
letter = letter.replace("<|DATE|>", date)
print(letter)

#Q: 3
st = "This is a string with double  spaces"
doubleSpaces = st.find("  ")
print(doubleSpaces)

#Q: 4
st = "This is a string with double  spaces"
st = st.replace("  ", " ")
print(st)

#Q: 5
letter = "Dear Sunil,\nThis python course is nice!\nThanks!"
print(letter)

#chapter:4
#Create a list using []
a = [1, 2, 4, 56, 6]
print(a)
#Access using index using a[0], a[1], a[2]
print(a[2])
#Change the value of list using
a[0] = 98
print(a)
#We can create a list with items of different type
c = [45, "Sunil", False, 6.9]
print(c)
#list sliceing
friends = ["Sunil", "Rohan", "Tom", "Sam", "Divya", 45]
print(friends[0:3])

#list method
l1 = [1, 8, 7, 2, 21, 15]
#print(l1)
#l1.sort()
#l1.reverse()
#l1.append(45)
#l1.insert(1, 45)
#l1.pop(2)
l1.remove(21)
print(l1)

#tuple in python
#creating a tuple using ()
t = (1, 2, 4, 5)
#t1 = () #empty tuple
#t1 = (1) #wrong way to declare a tuple with single element
t1 = (1,) #tuple with single element
print(t1)
#printing the elements of a tuple
#print(t[0])
#Cannot update the value of a tuple
#t[0] = 34 throws an error
#print(t)

#tuple methods
t = (1, 2, 4, 5, 1)
print(t.count(1))
print(t.index(5))

#practice set
#Q: 1
f1 = input("Enter Fruit Name 1: ")
f2 = input("Enter Fruit Name 2: ")
f3 = input("Enter Fruit Name 3: ")
f4 = input("Enter Fruit Name 4: ")
f5 = input("Enter Fruit Name 5: ")
f6 = input("Enter Fruit Name 6: ")
f7 = input("Enter Fruit Name 7: ")
myFruitList =[f1, f2, f3, f4, f5, f6, f7]
print(myFruitList)

#Q: 2
m1  =int(input("Enter Marks for Student Number 1: "))
m2  =int(input("Enter Marks for Student Number 2: "))
m3  =int(input("Enter Marks for Student Number 3: "))
m4  =int(input("Enter Marks for Student Number 4: "))
m5  =int(input("Enter Marks for Student Number 5: "))
m6  =int(input("Enter Marks for Student Number 6: "))
m7  =int(input("Enter Marks for Student Number 7: "))
myList = [m1, m2, m3, m4, m5, m6]
myList.sort()
print(myList)

#Q: 3
a = (2, 4, 5, 3, 2 )
a[0] = 45
print(a)

#Q: 4
a = (2, 4, 56, 7)
print(a[0] + a[1] + a[2] + a[3])
print(sum(a))

#Q: 5
a = (7, 0, 8, 0, 0, 9)
print(a.count(0))

#chapter:5
#selfe coding
a = {
"Sunil": "A coder",
"Marks": [1, 2, 5],
}
print(a)
print(a['Sunil'])
print(a.get("sunil"))
#print(a['sunil'])

#harry coding
myDict = {
"Fast": "In a Quick Manner",
"Sunil": "A coder",
"Marks": [1, 2, 5],
}
print(myDict['Fast'])
print(myDict['Sunil'])
print(myDict['Marks'])

#dictionary method
myDict = {
"Fast": "In a Quick Manner",
"Sunil": "A coder",
"Marks": [1, 2, 5],
"anotherdict": {'sunil': 'player'},
1: 2
}
#print(myDict.values()) #print the values of dictionary
#print(myDict.keys()) #print the keys of dictionary
#print(type(myDict.keys())) #type casting
#print(list(myDict.keys())) #list method

#metdods
#print(myDict.items()) #print the (keys, values) for all contents of the dictionary
#print(myDict.keys()) #print the keys of dictionary

print(myDict)
updateDict = {
    "Om": "friend",
    "sunil": "friend",
    "divya": "A Danser",
    }
print(myDict.update(updateDict))
print(myDict)

print(myDict.get("sunil"))
print(myDict.get("sunil2")) #return non as sunil2 is not present in tha dictionary
#print(myDict["Sunil2"]) #return error as sunil2 is not present in tha dictionary

#Sets in python
a = {1, 3, 4, 5,}
print(a)
print(type(a))

#empty dictionary
a = {}
print(type(a))
#empty set
b = set()
print(type(b))

b = set()
print(type(b))
#adding values to an empty set
b.add(4)
b.add(5)
b.add(5)
b.add(5)
print(b)

b = set()
print(type(b))
#adding values to an empty set
b.add(4)
b.add(5)
b.add(5) #reuseable value not printed to set
#b.add([4, 5, 6]) #list not adding to set
b.add((4, 5, 6)) #tupel adding to set
print(b) 

b = set()
print(type(b))
#adding values to an empty set
b.add(7)
b.add(4)
b.add(5)
#b.add(5) #reuseable value not printed to set
#b.add([4, 5, 6]) #list not adding to set
#b.add((4, 5, 6)) #tupel adding to set
print(b) 
print(len(b))

b.remove(5)
print(b)
print(b.pop())
print()

#union
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}
z = x.union(y)
print(z)

#intersection
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}
z = x.intersection(y)
print(z)

#practice set
#Q: 1
myDict = {
    "Pankha": "Fan",
    "Dabba": "Box",
    "Vastu": "Item"
}
print("Options are ", myDict.keys())
a = input("Enter the Hindi Word\n")
#print("The meaning of your word is:", myDict[a])
print("The meaning of your word is:", myDict.get(a))

#Q: 2
num1 = int(input("Enter number 1\n"))
num2 = int(input("Enter number 2\n"))
num3 = int(input("Enter number 3\n"))
num4 = int(input("Enter number 4\n"))
num5 = int(input("Enter number 5\n"))
num6 = int(input("Enter number 6\n"))
num7 = int(input("Enter number 7\n"))
num8 = int(input("Enter number 8\n"))
a = {num1, num2, num3, num4, num5, num6, num7, num8}
print(a)

#Q: 3
a = {18, "18", 18.1}
print(a)

#Q: 4
s = {20, 20.0, "20"}
print(s)
print(len(s))

#Q: 5
s = {}
print(type(s))

#Q:6
favLang = {}
a = input("Enter your favorite language Shubham\n")
b = input("Enter your favorite language Ankit\n")
c = input("Enter your favorite language Om\n")
d = input("Enter your favorite language Saurabh\n")
favLang['Shubham'] = a
favLang['Ankit'] = b
favLang['Om'] = c
favLang['Saurabh'] = d
#print(favLang)

#Q: 7
favLang = {}
a = input("Enter your favorite language Shubham\n")
b = input("Enter your favorite language Ankit\n")
c = input("Enter your favorite language Shubham\n")
d = input("Enter your favorite language Saurabh\n")
favLang['Shubham'] = a
favLang['Ankit'] = b
favLang['Shubham'] = c
favLang['Saurabh'] = d
print(favLang)

#Q : 8

#chapter:6
#if-elif-else ladder in python
a = 45
if(a>3):
    print("The value of a is greater than 3")
elif(a>7):
    print("The value of a is greater than 7")
else:
    print("The value of a is greater than 3 or 7")

#multiple if statements
a = 8
if(a>3):
    print("The value of a is greater than 3")
if(a>13):
    print("The value of a is greater than 13")
if(a>7):
    print("The value of a is greater than 7")
if(a>17):
    print("The value of a is greater than 17")
else:
    print("The value is not greater than 3 or 7")

#Q: age - 18
age = int(input("Enter your age\n"))
if age>18:
    print("Yes")
else:
    print("No")

age = int(input("Enter yur age: "))
if(age>45 and age<56):
    print("you cannot work with user")
else: 
    print("you can work with user")

#is and in uses
#a = None
#if (a is None):
#    print("Yes")
#else:
#    print("No")

a = [45, 56, 6]
print(45 in a)

a = 6
if(a==7):
    print("Yes")
elif(a>56):
    print("No nad Yes")
else:
    print("I am optional")

#Practice set
#Q: 1
num1 = int(input("Enter number 1: "))
num2 = int(input("Enter number 2: "))
num3 = int(input("Enter number 3: "))
num4 = int(input("Enter number 4: "))

if (num1>num4):
    f1 = num1
else:
    f2 = num4

if (num2>num3):
    f1 = num2
else:
    f2 = num3
if(f1>f2):
    print(str(f1) + "is greatest")
else:
    print(str(f2) + "is greatest")
    
#Q: 2
sub1 = int(input("Enter first subject marks\n"))
sub2 = int(input("Enter second subject marks\n"))
sub3 = int(input("Enter third subject marks\n"))

if(sub1<33 or sub2<33 or sub3<33):
    print("You are fail because have less then 33% in one of the subject")
elif(sub1+sub2+sub3)/3 <40:
    print("You are fail due to total percentage less than 40")
else:
    print("You Pass the exam")

#Q: 3
text = input("Enter the text\n")
if("make a lot of miner" in text):
    spam = True
elif("buy now" in text):
    spam = True
elif("click this" in text):
    spam = True
elif("Subscribe this" in text):
    spam = True
else:
    spam = False
if(spam):
    print("This text is spam")
else:
    print("This text is not spam")

#Q: 4

#Q: 5
names = ["sunil", "shubham", "rohit", "aditi"]
name = input("Enter the name to check\n")

if name in names:
    print("Your name is present in the list")
else:
    print("Your name is not present in the list")

#Q: 6
marks = int(input("Enter Your Marks\n"))
if marks>=90:
    grade = "Ex"
elif marks>=80:
    grade = "A"
elif marks>=70:
    grade = "B"
elif marks>=60:
    grade = "C"
elif marks>=50:
    grade = "D"
else:
    grade = "F"
print("Your grade is " + grade)

#Q:

#chapter:7
i = 1
while i<10:
    print("yes " + str(i))
    i = i + 1
    print("Done")

i = 1
while i<50:
    print(i)
    i = i + 1

i = 0
while i<5:
    print("Sunil")
    i = i + 1
    
fruits = ['Banana', 'Orang', 'Grapes', 'Mango']
i = 0
while i<len(fruits):
    print(fruits[i])
    i = i + 1

#fir loop

fruits = ['Banana', 'Orang', 'Grapes', 'Mango']
for item in fruits:
    print(item)
  
for i in range(1, 10, 2):
    print(i)

for i in range(10):
    print(i)
else:
    print("This is inside else of for")

 for i in range(10):
    print(i)
    if i == 5:
        break
else:
   print("This is inside else of for")

 for i in range(5):
    if i == 3:
        continue
    print(i)
 
i = 4
if i>0:
    pass
while i>6:
    pass
print("sunil is a good boy")

#practice set
#Q: 1
num = int(input("Ente the number"))
for i in range(1, 11):
    print(str(num) + " X " + str(i) + "=" + str(i*num))

#Q: 2
l1 = ["Harry", "Sohan", "Sachin", "Rahul"]
for name in l1:
    if name.startswith("S"):
        print("Hello " + name)
#Q: 3
#Q: 4
num = int(input("Ente the number: "))
prime = True
for i in range(2, num):
    if(num%i == 0):
        prime = False
        break
if prime:
    print("This number is prime")
else:
    print("This number is not prime")

#Q: 5
#Q: 6
# n! = 1 X 2 X 3 X ..... X n
# 5! = 1 X 2 X 3 4 5
num = int(input("Ente the number: "))
factorial = 1
for i in range(1, num+1):
    factorial = factorial * i
print(f"The factorial of this number is {factorial}")

#Q: 7
n = 3
for i in range(3):
    print(" " * (n-i-1), end="")
    print("*" * (2*i+1), end="")
    print(" " * (n-i-1))

#Q: 8
n = 3
for i in range(3):
    print("*" * (i+1))

#chapter:8
marks1 = [45, 98, 86, 77]
percentage1 = (sum(marks1)/400 )*100

marks2 = [75, 78, 88, 58]
percentage2 = (sum(marks2)/400 )*100
print(percentage1, percentage2)
#**
def percent(marks):
    p = ((marks[0] + marks[1] + marks[2] + marks[3])/400 )*100
    return p

marks1 = [45, 98, 86, 77]
percentage1 = percent(marks1)

marks2 = [75, 78, 88, 58]
percentage2 = percent(marks2)
print(percentage1, percentage2)
#**
def greet(name):
    print("Good day, "+ name)
greet("Sunil")
#**

def greet(name="Stranger"):
    print("Good day, "+ name)
greet("Sunil")
greet()

#practice set
#Q: 1
def maximum(num1, num2, num3):
    if (num1>num2):
        if (num1>num3):
            return num1
        else:
            return num3
    else:
            if(num2>num3):
                return num2
            else:
                return num3

m = maximum(25, 55, 2)    
print("The value of the maximum is " + str(m))

#Q: 2
def farh(cel):
    return (cel *(9/5)) + 32

c = 4
f = farh(c)
print("Fahreheit Temperature is " + str(f))

#Q: 3
print("Hello", end=" ")
print("How", end=" ")
print("are", end=" ")
print("you", end=" ")

#Q: 4
#Q: 5
n = 3
for i in range(n):
    print("*" * (n-i))

#Q: 6
#Q: 7
def remove_and_split(string, word):
    newStr = string.replace(word, "")
    return newStr.strip()

this ="      Sunil is a good     "
n =remove_and_split(this, "Sunil")
print(n)

#chapter:9
#1
f = open("Simple.txt", "r")
data = f.read()
print(data)
f.close()

#2
f = open("Simple.txt", "r")
data = f.read(5)
print(data)
f.close()

#3
f = open("Simple.txt")
data = f.readline()
print(data)
data = f.readline()
print(data)
data = f.readline()
print(data)
f.close()

f = open("another.txt", "w")
f.write("Please write this to the file")
f.close()

f = open("another.txt", "a")
f.write("I am appending")
f.close()

with open('another.txt', 'r') as f:
   a = f.read()

with open('another.txt', 'w') as f:
    a = f.write('me')
print(a)

#Q: 1
f = open("poems.txt")
t = f.read()
if 'twinkle' in t:
    print("Twinkle is present")
else:
    print("Twinkle is not persent")
f.close()

#Q: 2
def game():
    return 1250

score = game()
with open("highscore.txt") as f:
    highscoreStr = f.read()
if highscoreStr=='':
    with open("highscore.txt", "w") as f:
        f.write(str(score))

elif int(highscoreStr)<score :
  with open("highscore.txt", "w") as f:
        f.write(str(score))

#Q: 3
for i in range(1, 21):
    with open(f"table_multiplication_table_of_{i}.txt", 'w') as f:
        for j in range(1, 11):
            f.write(f"{i}X{j}={i*j}")
            if j!=10:
                f.write('\n')


#Q: 4
with open("sample.txt") as f:
    content = f.read()

content = content.replace("donkey", "$%^@$^#")

with open("sample.txt", "w") as f:
    f.write(content)

#Q: 5
words = ["donkry", "kaddu", "mote"]

with open("sample.txt") as f:
    content = f.read()

for word in words:
    content = content.replace( word, "$%^@$^#")

    with open("sample.txt", "w") as f:
        f.write(content)

#Q: 6 == 7h 50m
with open("log.txt") as f:
    content = f.read().lower()

if "good" in content:
    print("Yes python is present")
else:
    print("No python is not present")

#Q: 7
content = True
i = 1

with open("log.txt") as f:
    
    while content:

        content = f.readline()
        print(content)
        if "python" in content:
            print("Yes python is present")
            print(i)
        i+=1
        #else:
        #    print("No python is not present")

#Q: 7a 
#check for multiline line.
content = True
i = 1
with open("log.txt") as f:
        while content:
            content = f.readline()
        if "python" in content.lower():
            print(f"Yes python is present on line number {i}")
            print(content)
        i+=1 
        #else:
        #    print("No python is not present")


#Q: 8
with open("test.txt") as f:
    content = f.read()

with open("copy.txt", "w") as f:
    f.write(content)

#Q: 9
file1 = "copy.txt"
file2 = "test.txt"

with open(file1) as f:
    f1 = f.read()

with open(file2) as f:
    f2 = f.read()

if f1 == f2:
    print("File are identical")
else:
    print("File are not identical")

#Q: 10
filename = "sample.txt"
with open(filename, "w") as f:
    f.write("")

#Q: 11
oldname = "sample2.txt"
newname = "sunilllll.txt"
with open(oldname) as f:
    content = f.read()

with open(newname, "w") as f:
    f.write(content)
#Q: 11a
import os #remove old file 
oldname = "sample2.txt"
newname = "sunilllll.txt"
with open(oldname) as f:
    content = f.read()

with open(newname, "w") as f:
    f.write(content)

os.remove(oldname)

#chapter:10
class SchoolForm:
    formType = "SchoolForm"
    def printData(self):
        print(f"Name is {self.name}")
        print(f"Roll no is {self.roll_no}")

studentApplication = SchoolForm()
studentApplication.name = "Sunil"
studentApplication.roll_no = "12th" 
studentApplication.printData()

'''
check py class ctrl+cleck 
import pandas as pd

pd.DataFrame()

class SchoolForm:
    formType = "SchoolForm"
    def printData(self):
        print(f"Name is {self.name}")
        print(f"Roll no is {self.roll_no}")

studentApplication = SchoolForm()
studentApplication.name = "Sunil"
studentApplication.roll_no = "12th" 
studentApplication.printData()
'''

#game_example 8h 27m not run
#game_example 8h 27m
class Remote():
    pass

class player:
    def moveRight(self):
        pass

    def moveLeft(self):
        pass

    def moveTop(self):
        pass
    
remote1 = Remote()
player1 = player()

if(remote1.isLeftPressed()):
    player1.moveLeft()

#***** class attribute

class Employee:
    company = "Google"

sunil = Employee()
rajni = Employee()
print(sunil.company)
print(rajni.company)

Employee.company = "YouTube"
print(sunil.company)
print(rajni.company)

#***instance attribute

class Employee:
    company = "Google"

sunil = Employee()
rajni = Employee()
print(sunil.company)
print(rajni.company)
sunil.salary = 300
rajni.salary = 400
print(sunil.salary)
print(rajni.salary)

#**
#instens
class Employee:
    company = "Google"
    salary = 100

sunil = Employee()
rajni = Employee()
print(sunil.company)
print(rajni.company)
#sunil.salary = 300 #creting instance attribute salary for both the objects
#rajni.salary = 400
print(sunil.salary)
print(rajni.salary)

#****self parameter
class Employee:
    company = "Google"
    def getSalary(self):
        print("Salary is 100k")

sunil = Employee()
sunil.getSalary()
Employee.getSalary(sunil)

#****
class Employee:
    company = "Google"
    def getSalary(self):
        print(f"Salary for this employee working in {self.company} is {self.salary}")

sunil = Employee()
sunil.salary = 10000
sunil.getSalary() or Employee.getSalary(sunil)

#static
class Employee:
    company = "Google"
    def getSalary(self):
        print(f"Salary for this employee working in {self.company} is {self.salary}")
        
    @staticmethod
    def greet():
        print("Good Morning Sir")

sunil = Employee()
sunil.salary = 10000
sunil.getSalary() #or Employee.getSalary(sunil)
sunil.greet()


#Constructor
class person:
    def __init__(self, name, occ):
        print("Hey i am a person")
        self.name = name
        self.occ = occ
    def info(self):
        print(f"{self.name} is a {self.occ}")

a = person("Sunil", "Devloper")
b = person("Divya", "HR")
a.info()
b.info()

#**Practic Set**

#Q: 1
class Programmer:
    company = "Microsoft"

    def __init__(self, name, product):
        self.name = name
        self.product = product

    def getInfo(self):
        print(f"The name of the {self.company} programmer is {self.name} and the product is {self.product}")

Sunil = Programmer("Sunil", "Skype")
alka  = Programmer("alka", "Github")
Sunil.getInfo()
alka.getInfo()

#Q: 2
class Calculator:
    def __init__(self, num):
        self.number = num

    def square(self):
        print(f"The value of {self.number} square is {self.number **2}")

    def squareRoot(self):
        print(f"The value of {self.number} square root is {self.number **0.5}")

    def cube(self):
        print(f"The value of {self.number} cube square is {self.number **3}")

a = Calculator(3)
a.square()
a.squareRoot()
a.cube()

#Q: 3
class Sample:
    a = "Sunil"

obj = Sample()
obj.a = "alka"

print(Sample.a)
print(obj.a)

#Q: 4
class Calculator:
    def __init__(self, num):
        self.number = num

    def square(self):
        print(f"The value of {self.number} square is {self.number **2}")

    def squareRoot(self):
        print(f"The value of {self.number} square root is {self.number **0.5}")

    def cube(self):
        print(f"The value of {self.number} cube square is {self.number **3}")
    
    @staticmethod
    def greet():
        print("Hello there welcome to the best calculator of the world")

a = Calculator(9)
a.greet()
a.square()
a.squareRoot()
a.cube()
 
 #Q: 5
class Trane:
    def __init__(self, name, fare, seats):
        self.name = name
        self.fare = fare
        self.seats = seats

    def getStatus(self):
        print(f"The name of the train is {self.name}")
        print(f"The seats available in the train are {self.seats}")
    def fareInfo(self):
        print(f"The price of the ticket is : Rs {self.fare}")
    
    def bookTicket(self):
        if(self.seats>0):
            print(f"Your ticket has been booked! Your seats number is {self.seats}")
            self.seats = self.seats - 1
        else:
            print("Sorry this train is full! Kindly try in tatkal")

    def cancelTicket(self, seatsNo):
        pass    


panval = Trane("Panvel Express: 15065", 700, 300)
panval.getStatus()
panval.bookTicket()
panval.getStatus()

#Q: 6
class Sample:
    def __init__(self, name):
        self.name = name

obj = Sample("Sunil")
print(obj.name)

#chapter:11

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

class Programmer(Employee, Person):
    company = "fiver"
    def getSalary(self):
        print(f"No salary to programmers")

    def takeBreath(self):
        super().takeBreath()
        print("I am a Programmer so I am Breathing++..")

#p = Person()
#p.takeBreath()

#e = Employee()
#e.takeBreath()

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
class Employee:
    company = "Camel"
    salary = 100
    location = "Delhi"

#    def changeSalary(self, sal):
#        self.__class__.salary = sal

    @classmethod
    def changeSalary(cls, sal):
        cls.salary = sal


e = Employee()
print(e.salary)
e.changeSalary(455)
print(e.salary)
print(Employee.salary)

#propety decorator and getters
class Employee:
    company = "Bharat Gas"
    salary = 5500
    salarybonus = 400

    @property
    def totalSalary(self):
        return self.salary + self.salarybonus

e = Employee()
print(e.totalSalary)

#setters
class Employee:
    company = "Bharat Gas"
    salary = 5600
    salarybonus = 400

    @property
    def totalSalary(self):
        return self.salary + self.salarybonus
    
    @totalSalary.setter
    def totalSalary(self, val):
        self.salarybonus = val - self.salary

e = Employee()
print(e.totalSalary)
e.totalSalary = 5800
print(e.salary)
print(e.salarybonus)
