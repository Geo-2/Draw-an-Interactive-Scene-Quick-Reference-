# Overarching goal:

Draw an Interactive Scene.

---
## Guidelines:

<!-- - Use Adapta Nokeo for viewing this Document Easy syntax highlighter! -->

### Basic Requirements (Fullfil at least two...):
- Start by naming your new processing code with FirstLastName followed by interactive scene.

- Use of variables: 
    Avoid hard coded variables.
    
    Follow naming conventions. 
    
    All variables declared as global __before setup.__

        <!-- If you are going to use global variables.  -->
        One could use objects to organize, in future programs. 
        But don't let objects bog down your efficiency, if objects are taking too long to implement.
    
    Initialization will happen prior to setup or in setup depending on expectations.

        Of course, Use functions in a class, etc. 

- Conditionals: At least 3 conditional statements must be used that change the scene depending on user inputs.

- Loops: At least 1 loop (for or while) must be used to create a pattern.

<!--     Don't be lazy, and copy and paste. I know you love those for loops! -->

### Other requirements that are not so "basic"

2.	Have at least one object’s location determined relative to the size of the screen. (use built in variables (Height and Width).

3.	Use a Boolean variable.
        
        This can be in conjunction with user input or determined by other coding.

4.	Using relational or logical operators. 
        
        At least once in your code you need to use relational (!=, <, <=, ==, >, or >=) or logical operators (!, &&, ||) in your decision making.

5.	Have your scene interact with the mouse. 
        
        This might be something like changing their size according to the mouse, changing their color according to the mouse (i.e. rollovers), etc. This is intentionally vague to give you artistic freedom.

6.	Have your scene interact with the keyboard. 
        
        This could be as simple as using the keyboard as one giant reset button, or something much more complex. Once again, it's up to you. See Processing reference how to distinguish between keyboard keys… https://processing.org/reference/keyPressed_.html


### Independent Options (Must do both, but implement as you see fit!)

#### Variables can be used to represent states. 
-  
    Keep in mind the use of intergers:

        The most common usage is a Boolean, where a variable can only occupy one of two states (True or False). Integers can be used in the same way, if a developer ensures that only two different values are ever stored in that variable. (Typically using 0 and 1). If we want more than two possible states (or values) for a variable, an integer is a suitable choice [but_why_not_a_byte?__Issues????_FUNCTIONS_PASS_PARAMETER_STANDARDS,_that's_why?]. 
- 
    Create a variable called currentBack that will act as a 4-state variable (can only be equal to 0, 1, 2, or 3).

        Use this variable to control the background of your scene - a different background should be drawn depending on the value stored in that variable. Whenever the user right-clicks the scene, change currentBack to the next value: See Processing reference how to distinguish between mouse buttons… https://processing.org/reference/mouseButton.html

    ( 0 → 1    1 → 2     2 → 3    3 → 0).
    This should allow the user to cycle the background color with a right-click interaction.

    This may help with understanding state variables:
    http://learningprocessing.com/examples/chp05/example-05-08-edgespath

#### Animation: 
- 
    Use keyboard or mouse to animate part of the scene. Or have something in the scene animated automatically.

----


## Rubric:


### Functionality
8 pts
Exceptional
All basic requirements have been successfully implemented: proper name, variables, conditionals, loops, built-in, Boolean, operators, mouse, and keyboard.

### Logic / Efficiency
2 pts
Exceptional
The code is efficient without sacrificing readability and understanding. Excellent use of functions, loops, conditionals, and objects where appropriate to improve organization and/or efficiency.

### Communication / Readability
2 pts
Exceptional
The code is exceptionally well organized and very easy to follow. White-space and multiple files (tabs) are used to keep code organized. communication is clear and precise (unambiguous)

### Documentation (Comments in source code)
2 pts
Exceptional
Includes header and authors notes and code is well commented. All blocks of code have a general description and any complex or unique code has explanations.

### Independent option
4 pts
Exceptional
Two options have been successfully incorporated. It is clear the student has researched and implemented unique code to enhance the project.

### Peer Review
4 pts
Full marks
Both peers have received comments that are clear and specific. Several Kudo and Tweak comments are used so that the peer will be able to improve their project. Clear explanations are given that reveals deep understanding of the assignment and the required and independent coding for this project.
