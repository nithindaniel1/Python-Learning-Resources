# Python Programming Language

## 💻 Introduction

[Python](https://www.python.org/) is an interpreted **high-level general-purpose programming language**. Its design philosophy emphasizes code readability with its use of significant indentation. Its language constructs as well as its object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects.

## 💻 How to install & Configure

[![image](https://user-images.githubusercontent.com/44474792/123229167-ac6e8e00-d4f3-11eb-997b-a7149c967010.jpg)](https://youtu.be/AKVRkB0fot0)

## 💻 Resource Links to get started

### ⭐️ HackerRank

**[HackerRank](https://www.hackerrank.com/domains/python)** is a place where programmers from all over the world come together to solve problems in a wide range of Computer Science domains such as **Algorithms, Machine Learning, or Artificial Intelligence,** as well as to learn & practice different programming languages like **Python, JavaScript, C, C++, Java, Ruby** & much more...

[![image](https://user-images.githubusercontent.com/44474792/123522719-bd2e2800-d6dc-11eb-9175-3c9c62e44f9c.jpg)](https://www.hackerrank.com/domains/python)

### ⭐️ Scrimba

**[Scrimba](https://scrimba.com/)** is the next-generation platform for learning how to code. It is an interactive learning platform for mainly frontend developers. But they recently started adding courses for the backend as well. The screencasts enable learners to interact with the code directly in the player. The content on Scrimba is a mix between community generated tutorials, and courses initiated by the Scrimba team itself.

Some of them are:

- 🔰 [Python Basics](https://scrimba.com/playlist/peaXwtB) (9 Interactive Screencasts)
- 🔰 [Python | Introduction to Programming](https://scrimba.com/playlist/p5gW5AD) (21 Interactive Screencasts)
- 🔰 [Learn Python for free](https://scrimba.com/learn/python) (59 Interactive Screencasts)

[![image](https://user-images.githubusercontent.com/44474792/123522683-7809f600-d6dc-11eb-852f-184cb0f16421.jpg)](https://scrimba.com/learn/python)

### ⭐️ Programiz

**[Programiz](https://www.programiz.com/python-programming)** provides a beginner-friendly mobile app. It contains byte-size lessons and an integrated Python interpreter. **Learn Python: Programiz** is a free app that makes it easy to learn Python and try out what you have learned in real-time. If the platform suites, one can go for a subscription **Learn Python: Programiz Pro**, that offers challenges ans certification.

- 🔰 [Web Platform](https://www.programiz.com/python-programming)
- 🔰 [Android Application](https://play.google.com/store/apps/details?id=com.programiz.learnpython)
- 🔰 [IOS Application](https://apps.apple.com/app/apple-store/id1472188189?mt=8)

[![image](https://user-images.githubusercontent.com/44474792/123523554-da192a00-d6e1-11eb-887c-abcbf107c70b.jpg)](https://www.programiz.com/python-programming)

# **Example Programs**
## **1.Hello World Program**
Its a simple program  that describes how to input your name , age , designation and your three skills.You can workout this program as ice breaking one..
#### Source Code
```ino 
print("welcome to world of coding")
print("please fill the details")
name=input("enter your name -")
age=input("enter your age -")
designation=input("enter your designation -")
list=[]
for i in range(3):
    skills=input("please enter your skills:\n")
    list.append(skills)
print("my name is :",name)
print("my age is :",age)
print("I am ",designation)
print('i am mastered in ',*list,sep= "," )
```
#### output
![output 1](https://user-images.githubusercontent.com/81223681/135761760-e09c79ac-3ee4-4cfd-996d-cc11811a12e6.png)

## **2.Multiplication Table Program**
Yeah! Ice braked come on lets do an another program.This program is also a simple program but try it to ensure you are a good learner..
#### Source Code
```ino 
num=int(input("enter the nuber :"))
if (num%2)==0:
    print("{0} is even number".format(num))
    print ("multiplication table ")
    for i in range(1,11):
        print(num,'x',i,'=',num*i)
else:
    print("{0} is odd number".format(num))
    print ("multiplication table ")
    for i in range(1,11):
        print(num,'x',i,'=',num*i)
```
#### output
![output 2](https://user-images.githubusercontent.com/81223681/135762192-93e5053f-7f5d-4ed0-8520-ef64da794403.png)

## **3.Pattern Printing Program**
Lets Go to next program , In the next program we will  print a simple pattern 
#### Source Code
```ino 
rows=int(input("Enter the number of rows :"))
for i in range(0, rows):
    for j in range(0, i + 1):
        print("#", end=' ')
    print("\r")

for i in range(rows, 0, -1):
    for j in range(0, i - 1):
        print("#", end=' ')
    print("\r")

```
#### output
![output 3](https://user-images.githubusercontent.com/81223681/135836979-2cc3605e-ba5f-4b30-ad9d-35a669ccaa7f.png)

