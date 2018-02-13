# Henderson Middle - Intro to Computer Science  

## NextUp: Session 2 - Winter 2018  

### Introduction    
* Name  
* Age  
* Grade  
* Experience  
  - Any programming/coding experience?  

### Objectives  
##### What We'll Learn  

* What is a computer  
* What is coding/programming  
* Python  
* Raspberry Pi  

## Day One  

### Some Useful Ways to Solve Problems  

*10 min*  

Take a problem that at first, may seem overwhelming, or not "attackable" with a program, then break the problem into smaller manageable problems where we can use computation to solve. See how the smaller problems together make up the larger one. Think about computational thinking as useful ways to approach and solve problems using these steps: decomposition, generalization, recognize patterns, make plan (or algorithm) and carry it out.

Example, Clean the Whole House problem.  

### What is Computer Science  

Not just the study of computers. Really, it is the study of what can be computed. A major part of computer science is to design a solution, or step-by-step process for reaching a goal, design an algorithm, much like designing a recipe. And more...  

### What are Computers?  

Computers today, are devices that store and manipulate information and can do this because of programs. When we put info into a computer, it transforms the info into new, useful forms. Computer can then output or display the information we put into it.  

### Quick Computer History  

*10 min*

How far we've come. Early computers were tools (or mechanical devices) people used to help them calculate math problems. A modern computer is a device that can be programmed to perform a task. From Talley Sticks, to the Babbage Machine --end with Ada Lovelace, recognized as the first computer programmer.  

### What is a Computer Program?  

*5 min*  

Simply a set of instructions written by humans that causes the computer to perform some action. Coding and programming are synonymous.  

Discuss difference between Hardware and Software.  

### Out-of-Seat Programming Exercise  

*5 - 10 min*

Pick four volunteers to form two groups. Each group has a designated programmer and robot. Have each group stand in same area of the classroom. Point out a place in the room to be a destination. Explain that the programmer needs to give their robot step-by-step to get to the destination by telling the robot to walk forward (x amount of steps) or turn (90 degrees, left or right). The robot can only follow the directions given by their programmer.  

                  Go Forward 3 steps  
                  Turn left 90 degrees
                  Go forward 5 steps  
                  etc.  

Ask the class, which group was more efficient (the least amount of steps).   

***  

## Code  

*5 min*  

Code lets you communicate! In general, *code* is a system for transferring information. People use code to communicate with another, and between a person and a machine. Examples:  

* Morse  
  - light (flashlights, sun & mirrors, etc.)  
  - sound  
  - dots & dashes (telegraph machines)  
* Braille    
* Human Languages  
  - sign  
  - speech  
  - written
  - shorthand (stenography)  
* Computer languages  


### How Computers Manage Information   

*10 min*  

Computers *speak* using binary; where only the digits 0 and 1 are used. Zero is "coded" to mean OFF, one is "coded" to mean ON. Relate to a light switch.

Use the whiteboard to explain how computers translate numbers we use, decimal number system into the binary number system --by explaining the difference between the two by focusing on the place values.  

Decimal numbers use a **Base 10** system, meaning it uses a total of ten digits:

                    0 1 2 3 4 5 6 7 8 9  

Binary numbers use a Base 2 system, two digits:  

                    0 1

### Binary Flashcards  

*10 min*  

An all class activity to visually see how the binary number system operates by practicing a method that converts decimal numbers to binary. Ask for five volunteers. Give each volunteer a big binary flashcard (dark side of cards facing the class). Arrange the students to be in correct place value order. Write the number one on the board, use the cards and input from the class to have each volunteer flip the correct cards (turn "ON") to collectively show the number, one in binary. Do this for the numbers, 2 - 10. The class should progressively get quicker.  

### Python  

There are tons of different programming languages out there. We will learn how to write code in the Python programming language, an easy to read, understand and write language.  

| Py Concepts  |
|--------------|
| Data Types   |
| Variables    |
| Expressions  |
| Statements   |
| Functions    |
| Loops        |
| Conditions   |
| Objects      |
| Classes      |  

***  

### Getting Started with Chromebooks (trusty)  

Open up the terminal, help students get to the Hunderson folder.  

```bash  
mkdir your_name
geany helloworld.py
```  

#### HelloWorld.py  

Go over data types: strings, integers (INT), floats (FLOAT), boolean (BOOL). *see notes.py*  

Actual: Introduction to Python with the turtle module.  

***  

# Day Two  

Review definition of a computer program, concepts from LightBot, and Binary numbers. Segue into computers handling data, or information. Important to review what efficiency is, this will open conversation into quick computer history.  

## Computer History  

What is considered the first computer?  

What students have guessed before: the apple computer, super computer, and others.  

### Start at Tally Sticks  

Has anyone used tally marks? We can use them to help us keep track of counting something. One of the first *early* computers was **tally sticks**, prehistory! Early computers were tools to help people perform math. Tally sticks work in the same way as tally marks; they would help early humans count to numbers beyond the finger on their hand. They might have counted crops or other items. Humans then began to create more efficient tools such as the **Abacus**, a calculator.  

### Babbage & the 1st Programmer  

The transition from calculation to computation started with the **Babbage Machine**, an analytical *difference* engine created by Charles Babbage in 1836. Though, the machine was not actually built until the next century.  

Who is considered the first computer programmer? -The first computer programmer was Ada Lovelace. She actually wrote the programs for the Babbage machine.  

### Hardware vs Software  

Ask students if they have heard of hardware and software. Does anyone know the difference between the two? -Hardware makes up the physical components of a computer, whereas software makes up the programs, or instructions that tell the hardware what to do. They work together and make a computer a computer, so without one or the other we would not have computers! Bring up the point that hardware would be dead weight without the programs to control it.  

#### Engineers are Concerned with Building More Efficiently  

The advancements engineers made in hardware technology is categorized into generations.  

**First Generation (1946 - 1951) -** Fast forward to 1946, advancements in computer hardware brought in the first *commercial computers*, first generation. One of these computers was called the ENIAC (Electronic Numerical Integrator and Computer). Computers in this generation took up the space of two or even three classrooms and they needed several people to operate them!  

The main hardware component of these computers were **vacuum tubes**, switching devices with only two possible values, ON or OFF --think of lightbulbs. Pass around the vacuum tube example. Computers like the ENIAC had over 17,000 of these vacuum tubes! However, these pieces of hardware would overheat, burn out easily, so they would need constant replacement.  

**Second Generation (1959 - 1965) -** We had to come up with somewthing more efficient. Enter the 2nd Generation, 1959 - 1965. These electric computers, like the IBM 1401 were still big (took up about the same size as a teacher's desk). The vaccum tube as the main component of hardware was replaced by the more efficient **transistor** switching devices. Instead of having over 17,000 vacuum tubes, we only needed about 10,000 transistors to do the same job, and better. Transistors were more efficient at controlling the flow of electricty.  

[Transistor Activity](https://github.com/techemstudios/robious_ase/blob/master/intro_to_computer_science/Mini_Lessons/transistor_exercise.pdf)  

#### Transistors = the *Building Blocks* of Computers  

**Third Generation (1965-1971) -** The first *desktop computers*. Engineers found ways to combine transistors to form circuits. Computers in this generation, like the  Datapoint 2200 only needed to use ~3,500 tranistors. We also learned to combine circuits with other circuits, called *integrated circuits*. By combining more and more circuits, we get more switches. *Remember, circuits are made from combining transistors, which are like digital switching devices.* The more switches, the more zeroes and ones. Since computers handle data in zeroes and ones, computers were able to handle more, faster when we add more combined circuits. Engineers could further connect and minimize the space taken up with microchips.  

#### Moore's Law  

From the time of the invention of the Integrated Circuit, the # of circuits that could be placed on a single integrated circuit **DOUBLED** each year.  

***  

# Day Three  

### Logic Gates  

Review binary, value of 1 and zero and representations of each: 1 = On, True, Yes, etc.; 0 = Off, False, No, etc.  

Devices that perform basic operations on electrical signals. The switching logic in tranistors and circuits comes down to zero and one.  

### AND, OR, and NOT Gates  


How they operate, three ways we can represent them. Combine gates to form circuits.  

Start by asking the class to raise their hand if you are wearing shoes **AND** a shirt; most if not all hands should go up. Ask another, raise your hand if you are wearing shoes **AND** a hat; most hands should come down. Segue into how we can represent the AND gate.  

Use a whiteboard, or the flashcards to show how we can represent the logic of these gates:  

1. Logic Diagram Symbol  
2. Truth Table  
3. Boolean  

Move onto the Logic Gate Activity  

***  

