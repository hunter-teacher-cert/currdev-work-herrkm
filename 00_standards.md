# Standards selected:

## 7-8.CT.6 Design, compare and refine algorithms for a specific task or within a program.

This is a fairly central concept to programming in general, which fortunately can be applied at several different levels of complexity. 
The clarification in the standards document states:
  
> Algorithms can be represented in a range of formats, including flowcharts, pseudocode, or written steps. Planning the output of a program, 
such as with a storyboard or wireframe, is not sufficient on its own.

I took this to mean that there is an emphasis on the ability to understand the flow of a program to create appropriate code, compare similar programs, 
or improve an existing program. An activity I will be using early in my introductory programming course involves a program that classifies a provided
numeric average as an A, B, C, D, or F. The provided code does not work as expected:

```python
# Takes a user input for a percent score.
# Prints the appropriate letter grade for that score.

score = input("Please enter your score.\n")

if score > 90:
    print("A")

if score > 80:
    print("B")

if score > 70:
    print("C")

if score > 65:
    print("D")

else:
    print("F")
```

Students are expected to test the program using several different inputs. They should find the obvious error first (not converting the input to a numeric type), 
then test several different inputs (including edge cases) to figure out what the program does. When they understand, they will draw a flowchart diagramming 
the program's flow. Next, the groups or whole class discuss what the program is doing wrong and how to revise the control structures to fix it 
(change some `if` to `elif`). Finally, students will continue testing edge cases to notice that the cutoff for each letter grade should be inclusive, not exclusive.


## 7-8.CT.9 Read and interpret code to predict the outcome of various programs that involve conditionals and repetition for the purposes of debugging.

In the initial introduction of conditionals, students will play an unplugged game to practice reading and understanding conditional flow. 
This is adapted from an activity that one of my Methods groups shared this summer, where students are provided with silly directions
to follow under certain circumstances based on an input value. In this version, we practice a few code blocks as a group
to ensure that students know how to read the indentation and structure. Below I have shared a sample of a code block and the associated questions that students would
answer to demonstrate their understanding. Students are provided with different inputs to follow, in this case 9, 3, and 7. 
Students complete increasingly complex versions of this task and finish by creating one of their own using at least 4 conditions and one that cannot be reached.

Round 2:

```
   if input > 5:
A......Stand up (on the floor)
B......Hop on one foot 3 times
       if input == 7:
C..........Pat your head
           if input < 7:
D..............Spin in a circle
 
   if input < 7:
E......High five a neighbor
```

2a: input = ______
Directions completed: ____________________________________

2b: input = ______
Directions completed: ____________________________________

2c: input = ______
Directions completed: ____________________________________


What values are will cause you to high five a neighbor? ________________


What instruction is impossible to reach? ________________ 
