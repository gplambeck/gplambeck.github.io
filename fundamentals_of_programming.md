---
theme: time-machine
---

# Unit 1 Fundamentals of Programming in Python

----------

I’ve organized my portfolio like a table of contents in a book and modeled the paths to the content after the directory standard used for file management with computers. Each unit is sectioned into modules containing the topics that were explored for the unit. Each module and topic in the modules are linked to their specific section of the page. The reason for this order is to make navigating each page and the entire portfolio site user friendly. The paths of each topic can be followed the same way paths of a file can be followed on a computer to find its location.

The topics explored in this unit are:

- [Module 01](#module-01)
  * [Python Basics](#python-basics)
  * [Turtle](#turtle)
- [Module 02](#module-02)
  * [Calculation](#calculation)
- [Module 03](#module-03)
  * [Creating A Simple Game](#creating-a-simple-game)
  * [Password Generator](#password-generator)
- [Module 04](#module-04)
  * [Collatz Sequence](#collatz-sequence)
  * [Comma Code](#comma-code)
  * [Character Picture Grid](#character-picture-grid)
- [Module 05](#module-05)
  * [Functions](#functions)
  * [Encryption/Decryption](#encryption/decryption)
- [Module 06](#module-06)
  * [Strings and Exception Handling](#strings-and-exception-handling)
  * [Password Manager Program](#password-manager-program)

I have chosen these particular pieces to demonstrate the progress I have made in learning the Python language. Each of these pieces represents how I started with learning the basics and how the different codes work and then advancing by applying what I have learned to create useful programs. My goals were to improve the skills I had already taught myself and to understand the language better. I have successfully accomplished these goals by following and understanding the examples in class and in the book *Automate The Boring Stuff With Python*. To explore my new skills further, I would also continue to use the book I was teaching myself from, *Beginning Python From Novice to Professional*, and research codes on the internet to find ways of enhancing my programs.

The one thing I would like someone to notice about my portfolio is that I don’t just accomplish what needs to be done, I continue to go beyond the lesson to learn more and continue to advance the skills I start out with. I think that once basic skills are mastered, the only way to keep these skills is by continually using them and finding new ways to advance them. I feel that this collection of work really reflects my abilities and what I have achieved so far. I came into this class with a little understanding of Python and some background in programming. This collection flows from starting with some simple basic skills, progresses by using those skills and exploring further how to add to them, and then combining multiple projects into one to result in a fully functioning program.

## Module 01
### Python Basics

----------

I selected these practices because they demonstrate how far I have come since the beginning of the semester. Practice 1 demonstrates storing a message in a variable and printing the message to the screen, and then changing the value of the variable and printing the new value to the screen. I created this by first naming my variable spam and assigning it the message as its value, then calling the print function on spam as seen here:
```python
spam = "Hello World!"
print(spam)
```
Practice 2 demonstrates how to print quotation marks to the screen. This is done by using **_escape quotes_**, single quotes enclosing the string.
```python
print('Obi-Wan Kenobi once said, "You\'ve taken your first step into \
a larger world."')
```
I also used (\\) to tell Python that the apostrophe is a character in the string and not the end of the string. In addition, I used the backslash by itself at the end of the line to tell Python that I want to break to the next line but to ignore the break when printing the string. This style is particularly important to me when writing code because text editors usually open as a small window. By confining my texts to a standard space, someone reading my code wouldn’t need to scroll to the side to read what is hidden at the side of the window or enlarge the window and fill their limited screen space.

Practice 3 demonstrates the importance of knowing the difference between an integer and a string. This is important because only strings can be concatenated. If the value of a variable is an integer and it is called upon in a string, the variable must be converted to a string using ```str(fave_num)``` before the variable can be concatenated in the string.

Practice 4 demonstrates the ```len()``` function which returns an integer value of the number of characters in a string.

Since most of the books I have read about Python start with these same basic practices, these practices relate to what I have learned before. I would like to remove this basics section from this collection because it doesn’t really reflect the full potential of my skills. This section just reflects the foundation of my later works. Starting here and progressing on shows how my projects progress and advance from the foundations I start with.

### Turtle

----------

![Image](image/Olympic_Logo.png)

I selected this piece of work because I have never typed instructions to the computer before to draw an image. Even though point, click, and drag are technically instructions to the computer, this is manually speaking to the computer in a language both I and the computer understand. I created this image by first making a variable called *my_turtle* to create a pen that will draw the circles. Then, I used *.circle()* to draw the circles of a radius I specify in the parentheses. I used *.backward()*, *.forward()*, and *.left()* to move my pen into the positions I specify in the parentheses to draw the circles at their locations shown above. I used *.up()* to lift the pen up and stop drawing to the screen when moving the pen and *.down()* to put the pen down and draw the circle. To change the color of the circles, I used *.color()* and specified the color in the parentheses. To make the code easy to follow, I grouped the codes by each ring color. Here is an example of how the blue ring was made:
```python
#Blue ring
my_turtle.up()	#lifts up the pen
my_turtle.backward(225)	#moves backward 225 without drawing
my_turtle.color('blue')	#sets the color blue
my_turtle.down()	#puts the pen down
my_turtle.circle(100)	#draws a blue circle of radius 100
```
Learning how the numbers affect the forward and backward movements was particularly important to me during the process of creating this work. Having the correct amount of spacing between the circles was a problem I encountered when creating this image. To find the right amount of spacing, I did a lot of trial and error inputting the numbers. Once I saw the right amount of space between two circles, I calculated the rest of the movements based on this initial number. Doing these calculations relates to what I learned about movement on a graph in algebra and angles in trigonometry.


[Module 01 Files](https://github.com/gplambeck/unit_1/tree/master/module01)

## Module 02
### Calculation

----------

The goal here was to use Python's math operators to estimate the number of trees in Sacramento.

[Module 02 Files]()

## Module 03
### Creating A Simple Game

----------

This simple game of Rock - Paper - Scissors, is a good example of working with conditionals. The entire program relies on evaluating if a condition is met then do this else if the condition is not met then do something else. I decided to take the progaram a step further and code it to that popular game of Rock - Paper - Scissors - Lizard - Spock.

### Password Generator

----------

The password generator is a good example of how random items from a list can be chosen by the computer. Since this is a *password* generating program, it was also useful to lean how to use the .replace(str1, str2) and .capitalize() methods to generate more secure passwords. As a challenge project, I made a program that gives the computer 60 seconds to guess what the password is and displays the number of guesses after a user inputs a 4 character password composed only of lower case letters.

[Module 03 Files]()

## Module 04
### Collatz Sequence

----------

This program is an example of how to define a function and how to use the  **_try_** and **_except_** statements to validate the input. The collatz(number) function divides an even input integer by 2 or multiplies and odd input integer by 3 and adds 1. The program calls on this function until the the num variable is equal to 1.

### Comma Code

----------

A function that takes a list value as an argument and returns a string with all the items separated by a comma and a space, with 'and' inserted before the last item. This is a good example of how to type a list once and call on the values without typing each value over again in the code.

### Character Picture Grid

----------

This function prints an ASCII image. The image is created by printing the values of each list that are stored in a list. This project was a good example of getting specific values from a specific index in a list. To print my second image, I printed the image on paper and sketched a grid of each character that was needed for the image. I then used my grid to enter each value of each list and position the lists in the main list so that when the function was called the characters would print the resulting ASCII image.

[Module 04 Files]()

## Module 05
### Functions

----------



### Encryption/Decryption

----------



[Module 05 Files]()

## Module 06
### Strings and Exception Handling

----------



### Password Manager Program

----------



[Module 06 Files]()


#### Course Units

----------

1. [**Fundamentals of Programming in Python**](./fundamentals_of_programming.md)
2. [Internet of Things (IoT)](./internet_of_things.md)
3. [Secure Scripting](./secure_scripting.md)
4. [Data Analytics](./data_analytics.md)
5. [Python Hackathon](./python_hackathon.md)

[About Me](./README.md)
