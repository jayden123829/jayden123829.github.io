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















## Vocabulary



















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


