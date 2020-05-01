---
title: Coding Information
description: Page by Bridger Parker, Josh Goodfellow, and Austin Maze
published: true
date: 2020-05-01T02:32:04.168Z
tags: 
---

# Useful Coding Information
 by Bridger Parker, Josh Goodfellow, and Austin Maze

Programming Basics:
---

<!-- Intro Paragraph here, pictures are just html embedded if you add any. you have to click the img folder to the left and upload them before they're used though -->

**Branching:**
> Branching is basically cause and effect. The computer checks for conditions and those conditions determine what next choice is made. Think of it like a school day, you have your regular routine: wake up, put on clothes, eat food, brush your teeth, go to school, come home, do homework, eat dinner, go to bed. But what happens if your routine is changed? What if on Tuesdays you have a doctors appointment, how would that change your day? In coding, Tuesday would be a “branch” that diverts from the normal routine. 

**Component:**
>When talking about programming a component is an easily noticeable part of a much bigger program that provides a certain function. A car could be a component because it provides a spot to sit (an input) and it also takes somebody from one point to another (it’s function). A car also needs gas to be able to move and it even has a set speed that it cannot go over (it’s characteristics). A car has an engine, brakes, AC, etc… and each of these have their own separate functions as well. But this engine/other parts requires their own quantity of gas as their “input” then it performs its series of steps and ends with carbon monoxide as it’s “output”.  

**Event handler:**
>This is a procedure that controls the event and then makes decisions based on what should happen if that event occurs. Most of the time it is a software procedure that processes things like movements of the mouse or keystrokes. When you think of an event handler in terms of websites it makes those websites content more dynamic. 

**Loop:**
>When you think of a loop you think about something that continues to repeat, again and again. In coding loops allow something to be repeated until you give directions or instructions for it to stop. This could mean that it will loop a certain number of times or it could mean that it will continue to loop until a condition that you have given is met. Loops are used to make programs even more productive and/or effective. 

**Message passing:**
>Message passing means to send a message to a process (a group of instructions that are being processed by a computer's processor). This message being passed can be a: function, object, parallel process, subroutine, or a thread and it can be used to call another process either directly or indirectly. It is a type of communication that is used in object-oriented and parallel programming. 

**Method:**
>Methods only really appear in object-oriented programming languages because in other programming languages it is called a function or procedure. The only big difference between a function/procedure and a method is that a method is ALWAYS correlated with a class. 
Object methods are only able to acquire data that is known by that certain object. By this process it preserves the integrity of data between sets of objects in a program. Methods can also be used again in many other objects. Think about Methods in terms of a “video snippet object” that handles functions that are related to clips of this movie snippet, this object would have methods like: play, pause, and stop. 

**Overloading:**
>Overloading is a feature that allows a word or symbol to have a number of different meanings, but it depends on how it is used. It is meant to help avoid redundant code. By overloading it allows for more clarity, gets rid of complexity, and even strengthens the runtime performance. 
This term of “overloading” is used most when considering operators and how they can act differently based on the class or data type of the operands. An example can be the equation 
“a + b” it can mean different things but this all depends on what the values of “a” and “b” are. Are they just simple numbers or are they complex structures of data?
Overloading can only be used in certain programming languages because not all support it. Most object-oriented languages like Java and C++ use overloading but it is only one “form”. 

**Sequence:**
>Sequence simply means having something in a logical order. When you apply this definition to programming it means that a computer reads through a program, line by line, reading it in the order that you have put it in. If you don’t give it specific instructions to stop reading at a certain point and read somewhere else it will continue to read, line by line. The computer is sequencing by having certain steps that are carried out in order. 

<br />
Object Oriented Programming:
---

Most of the code-related projects done in GIMM are created using the Object Oriented Programming (OOP) technique. This is a computer programming method that allows developers to create different classes, or “objects”, that can interact but have independent functionality. Objects are instances of a class that can be viewed as variables that are able to store data as well as complex systems. This technique allows programmers to make edits and additions to pieces of the code without it impacting other classes of the code as long as you adhere to the main principles of OOP.

**Class:**
>In object-oriented programming, a category of objects. For example, there might be a class called shape that contains objects which are circles, rectangles, and triangles. The class defines all the common properties of the different objects that belong to it.

**Object:**
>Generally, any item that can be individually selected and manipulated. This can include shapes and pictures that appear on a display screen as well as less tangible software entities. In object-oriented programming, for example, an object is a self-contained entity that consists of both data and procedures to manipulate the data.

**Pattern:**
> The term pattern relates to the use of patterns in architecture. A pattern is the formalization of a problem/solution pair, used to make an object-oriented design decision. The purpose of a pattern is to codify existing design knowledge so that developers are not constantly reinventing the wheel. Also, by naming these patterns, it eases communication among developers. The term pattern was first coined by Christopher Alexander et al. in 1977. * [Source: Patterns in Object-Oriented Development]

**Encapsulation:**
>Encapsulation is ensuring that the information stored within a class is kept private and is accessed indirectly through public methods. The figure below shows this with the “Mouse class” which has private variables that can’t be accessed by the cat or cheese objects. However, there are public functions that allow these variables to still be altered by the interaction.

<img src="/images/encapsulation.png" width="300px" style="margin-left: 50px" alt="Using encapsulation, the public functions are able to access the Mouse's private variables." />
<br />

**Abstraction:**
>An abstraction is a concept or method that isn’t associated with any particular instance of an object. A fundamental property of abstraction is that a class does not need to know the details of another class, only the interface of the class.

**Inheritance:**
>Inheritance is used when you have several classes that all need to have similar methods and data stored within them. This concept allows for a programmer to make a “parent” class that will have all the data that is needed in every “child” class. These children are then able to add more functionality beyond what is defined by the parent.

**Polymorphism:**
>Polymorphism is similar to inheritance with the main difference being instead of purely inheriting the values of the parent class, with polymorphism a child will override the functionality of the parent class. This allows for many objects that all have similar variables and functions, but some are able to be changed drastically, such as the Enemy class defined in the images below has a basic Move() function that is overridden for any instance of Enemy_1.

<img src="/images/enemycode.png" width="275px" height="400" style="margin-left: 50px" alt="This Enemy_1 is a an Enemy class object and overrides the Move() function of the base enemy." />
<img src="/images/enemytype.png" width="275px" height="400" alt="This Enemy_1 is a an Enemy class object and overrides the Move() function of the base enemy." />
<br />

**Advantages of Object-Oriented Programming:**
>One of the principal advantages of object-oriented programming techniques over procedural programming techniques is that they enable programmers to create modules that do not need to be changed when a new type of object is added. A programmer can simply create a new object that inherits many of its features from existing objects. This makes object-oriented programs easier to modify.

<br />
Other Types of code learned through the GIMM program:
---

**Action script:**
>Action script is a coding language most commonly associated with Flash. It’s basically a simpler version of C#. Most, if not all, Flash programs are 2D. Unfortunately, Flash as a web service will soon be filtered out of most web browsers by the end of the year 2020. Though, Flash and Action Script remain to be great animation tools and a great start for beginner programmers.

<img src="/images/ripflash.jpg" width="200px" style="margin-left: 50px"/>


**Javascript & Bootstrap:**
>Javascript is the coding language used most commonly for web pages. Javascript is a very similar language to C# using a lot of the same terminology for a lot of the code. For example, doing functions and “if’ statements or declaring variables and strings are done in the same way for both languages. Bootstrap is an open source CSS that you can integrate into web pages to make them look more appealing. It also comes with several prebuilt functionalities to help making a website from scratch a lot easier. 

<img src="/images/javascript.png" width="200px" />

**ChucK:**
>ChucK is a digital audio based programming language. ChucK plays off of C# but introduces a few new things that makes creating sounds and music interesting. With ChucK, you can generate totally new sounds, or use samples and tweek with them such as slowing them down, speeding them, changing their pitch, etc. 

<img src="/images/chuck_logo3.jpg" width="200px" style="margin-left: 50px"/>

**Arduino:**
>Arduinos are small computers that interact with the physical world in some way. There are many different types of Arduinos and they all are made to perform different tasks. Some Arduinos are made to send out bluetooth signals, some are made for music, and the list goes on. In GIMM, we learn how to code and assemble these little pieces of equipment to complete different tasks. Some of these tasks include turning on lights, creating moving pieces for a board game, and even a usable joystick for our own games.

<img src="/images/arduino.png" width="300px" style="margin-left: 50px"/>

Sources:
---

**Bridger’s:**

https://www.oodesign.com/
https://stackoverflow.com/
https://medium.com/@cancerian0684/what-are-four-basic-principles-of-object-oriented-programming-645af8b43727
https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/

**Austin’s:**

https://support.microsoft.com/en-us/help/4520411/adobe-flash-end-of-support
https://www.arduino.cc/

## Student Expectations and Experiences
GIMM (Games Interactive Mobile Media), is a program centered around the development process for games and applications for all devices. Similar to the industry, each year new techniques and tools are introduced to keep students as up to date as possible. Because of this, students may be afraid of what they are getting into, which is where this page comes in. Here you can prepare for what expectations and tips for how to succeed.

https://www.webopedia.com/Programming/Object_Oriented_Programming
https://en.wikipedia.org/wiki/Branch_(computer_science)
