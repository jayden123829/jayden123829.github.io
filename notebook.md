## Table of Contents
- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
  - [Headings](#headings)
  - [Text Formatting](#text-formatting)









- ## Blocks
hat block is a block with a curved top and a single notch at the bottom that starts a script or program when a specific event occurs, acting as a listener for triggers and always sitting at the very top of a stack of blocks, such as the when green flag clicked block

 Stack Blocks/command block is a rectangular block with a notch on top and a bump on the bottom that performs a specific action or command and connects to other commands by snapping in sequentially above or below them, such as the move 10 steps block.
 
 C-Block is a control block shaped like the letter "C" with an open mouth in the middle that loops or conditionally runs code, meaning it physically wraps around other blocks placed inside its mouth to dictate how they execute, such as the repeat 10 block.
 
Reporter / Oval Block is an oval, rounded rectangle block that holds and outputs a value like a number or a text string, meaning it cannot stand alone and must be dropped directly into the matching round input slots of other blocks, such as the x position block.

Boolean / Hexagonal Block is a six-sided block with pointed ends that reports a true or false condition, using its unique hexagonal shape to ensure it can only be dropped into matching pointed condition slots so programmers cannot accidentally input regular text or numbers, such as the touching mouse-pointer? block.

Repeat Block is a C-shape loop block that runs a specific set of instructions a set number of times, where the target action blocks are placed inside its mouth and a number value is typed into its input window to dictate the loop count, such as a repeat 4 block used to draw the four sides of a square.

Wait Until Block is a rectangular stack block with a hexagonal input slot that pauses the script execution completely until a specific requirement is met, requiring a Boolean condition to tell the program when it is allowed to proceed, such as the wait until <key space pressed?> block.

If Then Block is a C-shape block with a hexagonal input slot that checks a specific condition before running code, meaning that if the hexagonal condition evaluates to TRUE, the program runs the blocks tucked inside its mouth, but if it evaluates to FALSE, it skips them entirely, such as the if <touching color red?> then [say "Ouch!"] block.

Forever Block is a C-shape block with a flat bottom and no bottom bump that loops the code inside it endlessly for the entire duration of the program, which programmers use to constantly check for inputs or keep background gameplay elements running, such as a forever [next costume, wait 0.1 seconds] block.





## Concepts

Sequence is the specific order in which a computer executes commands, running sequentially from top to bottom. You can think of it as the "step-by-step" recipe for your robot; if you mix up the steps, the final result won't turn out right. For example, to move a robot safely past an obstacle, you must command it to Turn Left before you command it to Drive Forward, because doing these steps in reverse will cause the robot to crash.

Parameters are the inputs or extra pieces of information passed into a command to customize or modify its behavior. These act like specific settings or dials you tweak on a command to tell it exactly how much or how far to do something. For example, in the command Drive Forward (distance), changing the parameter from 5 inches to 10 inches instantly changes the instruction and makes the robot drive twice as far.

A Loop, or Iteration, is a programming structure that repeats a block of instructions a set number of times or until a specific condition is met. These act as clever shortcuts in your code that let you repeat actions without having to type the exact same commands over and over again. For example, instead of writing Drive Forward and Turn Right four separate times to draw a square, you can place those two commands inside a single Repeat 4 Times loop.

Sensors are physical hardware components that allow a robot to detect and measure physical properties of its surrounding environment. They act as the eyes, ears, and hands of a robot, allowing it to actively notice what is happening around it. For example, a bumper switch sensor can detect the exact moment a robot physically collides with a wall, while an ultrasonic sensor measures the distance to figure out how far away that wall is.

A Boolean is a data type that can only have one of two values, TRUE or FALSE, while a Condition is an expression that evaluates to a Boolean to control program flow. This acts like a digital yes-or-no question that the robot checks to figure out what it should do next. For example, the conditional statement Is Bumper Pressed? evaluates to TRUE if the robot hits a wall, and FALSE if it is moving freely through open space

Sense → Think → Act is the continuous behavioral loop where a robot gathers data from its environment, processes that data to make a decision, and executes a physical response. This describes the three-step cycle of how a robot lives its life: it takes in information, decides what to do about it, and then physically moves. A perfect example of this is a self-driving car that sees a red light (Sense), decides it needs to stop (Think), and engages the physical brakes (Act).

Comparisons use mathematical operators like <, >, or == to compare two separate values and produce a TRUE or FALSE Boolean output. In simple terms, it means checking two different numbers against each other to see which one is bigger, smaller, or if they are perfectly equal. For example, a robot can constantly check if Current Battery Level < 20%, and if that statement evaluates to TRUE, it will stop its current task and head straight to the charging dock.

Coordinates are a set of numerical values, typically X for horizontal and Y for vertical, that pinpoint an exact location on a grid or map. They function just like a robot's personal GPS on its playing field, telling it exactly where it stands at any given moment. For example, setting a robot's destination coordinates to X = 5, Y = 10 commands it to move exactly 5 units to the right and 10 units up from its starting origin point of (0,0).

Patterns involve recognizing repeating sequences, regularities, or behaviors in a problem or system to build more efficient algorithms. This means finding a predictable rhythm in a task so you can write smarter, cleaner, and shorter code to handle it. For example, recognizing that a warehouse robot always turns 90 degrees right after picking up an item allows you to build a standardized "pickup-and-turn" pattern directly into its main navigation software.


## Vocabulary
VR Robot, PlaygroundDefinition: A VR Robot is a virtual robot controlled by a program within a simulated environment. A Playground is the specific virtual grid, map, or arena where the VR Robot operates and interacts with objects.In My Own Words: The VR Robot is the digital robot you program, and the Playground is the digital world or map where it drives around and performs tasks.Example: Programming a VR Robot to navigate the "Grid Map" Playground without hitting any walls.

VR Robot, PlaygroundDefinition: A VR Robot is a virtual robot controlled by a program within a simulated environment. A Playground is the specific virtual grid, map, or arena where the VR Robot operates and interacts with objects.In My Own Words: The VR Robot is the digital robot you program, and the Playground is the digital world or map where it drives around and performs tasks.Example: Programming a VR Robot to navigate the "Grid Map" Playground without hitting any walls.

Behavior, CommandDefinition: A Behavior is an action or series of actions performed by a robot (such as moving or turning). A Command is a specific instruction written in code that tells the robot to execute a behavior.In My Own Words: A command is the exact line of code you write, and the behavior is what you physically see the robot do because of that code.Example: Giving the drive_for command results in the robot performing the behavior of moving forward for 200 millimeters.

DrivetrainDefinition: A Drivetrain is the system of components—including motors, wheels, and gears—that enables a robot to move and turn.In My Own Words: The drivetrain is the part of the robot's body that controls its wheels so it can drive around the playground.Example: Using drivetrain blocks to control the speed and direction of the robot's movement.

Loop, IterationDefinition: A Loop is a programming structure that repeats a block of code multiple times or until a condition is met. An Iteration is a single, complete repetition of the code inside that loop.In My Own Words: A loop is the code block that makes things repeat, and an iteration is each individual time the robot goes through that repeating list of steps.Example: If a repeat loop runs 4 times to draw a square, the program goes through 4 iterations of driving and turning.

Sensor, Bumper SensorDefinition: A Sensor is a device that detects and measures physical data from the environment and sends it to the robot's controller. A Bumper Sensor is a specific type of physical touch sensor that detects when a robot collides with or presses against an object.In My Own Words: A sensor is how the robot feels or sees the world around it, and a bumper sensor is a specific button on the front or back that tells the robot when it bumps into a wall.Example: The robot drives forward until its Bumper Sensor hits a wall, which sends data to the program to stop driving

Boolean, Condition, TRUE, FALSEDefinition: A Boolean is a data type that can only hold one of two values: TRUE or FALSE. A Condition is a statement or check in a program that evaluates to a Boolean value. TRUE represents a verified statement, while FALSE represents an unverified statement.In My Own Words: A condition is like a yes-or-no question the robot asks itself. If the answer is yes, the result is TRUE; if the answer is no, the result is FALSE.Example: The program checks the condition "Is the bumper pressed?". If the robot is touching a wall, the Boolean result is TRUE. If it is in open space, the result is FALSE.

Distance Sensor, ThresholdDefinition: A Distance Sensor is a device that uses lasers or ultrasonic waves to measure how far away an object is from the robot. A Threshold is a specific numeric value or limit used to trigger a change in behavior when sensor data crosses it.In My Own Words: The distance sensor tells the robot how many millimeters away a wall is, and the threshold is the exact danger-zone distance you set to tell the robot when to stop or turn.Example: The robot uses a Distance Sensor to scan ahead, and when the reading drops below a threshold of 50mm, it turns right to avoid a crash.

Coordinate Plane, X-axis, Y-axis, X-coordinate, Y-coordinateDefinition: A Coordinate Plane is a two-dimensional grid system formed by the intersection of a horizontal line (X-axis) and a vertical line (Y-axis). An X-coordinate measures horizontal position, while a Y-coordinate measures vertical position.In My Own Words: The coordinate plane is the grid map the robot drives on. The X-axis is the side-to-side line, the Y-axis is the up-and-down line, and the coordinates tell you exactly where the robot is standing on that grid.Example: A playground grid center starts at (0,0). If the robot drives right, its X-coordinate increases; if it drives up, its Y-coordinate increases.

Location SensorDefinition: A Location Sensor is a built-in device or feature that reads the exact X and Y coordinates and heading angle of the VR Robot on the playground grid.In My Own Words: The location sensor acts like the robot's personal GPS, constantly telling the program exactly where the robot is on the map.Example: Using the Location Sensor to stop the robot precisely when its X-coordinate reaches 400m

CommentDefinition: A Comment is a text note written inside the code by the programmer to explain how the program works; it is completely ignored by the robot when running the project.In My Own Words: A comment is a sticky note left in the code to remind yourself or explain to others what that part of the program is supposed to do.Example: Adding a # This code makes the robot turn around comment right above a turning block.

Eye SensorDefinition: An Eye Sensor is a device on the robot that points in a specific direction (like front or down) to detect the presence of objects, distance, and specific colors.In My Own Words: The eye sensor is the robot's camera that lets it "see" what color tile it is driving over or if there is an object right in front of it.Example: Using the down-facing Eye Sensor to stop the robot the moment it drives over a red line on the playground floor.

Conditional StatementDefinition: A Conditional Statement is a programming structure (such as an if-then or if-then-else block) that directs the robot to run specific parts of code only if a certain condition is true.In My Own Words: A conditional statement is an "if this happens, do that" rule that lets the robot make decisions on its own while driving.Example: An if-then conditional statement that says: "If the bumper is pressed, then reverse the robot."




## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft
- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |
|--------------|------------|-----------------| 
| Homework 1  | Done #  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.


