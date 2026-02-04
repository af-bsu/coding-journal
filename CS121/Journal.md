# Coding Journal for CS121
## Module 1
### 2026-01-12
This is a test of using Obsidian for a coding journal. This entry can be ignored.
### 2026-01-15
#### Textbook notes
Computer programs execute instructions **one at a time** -- they do not execute all at once, but they give the impression of it due to modern computer speeds

**Inputs** are data that a program collects from the user (file uploads for example) or its environment (keyboards, touchscreens, network, etc.). Programs then process this data and generate an output

Data is often referred to using **variables**
Any sequence of instructions to generate a desired solution is called an **algorithm**

A **Java program** begins by declaring a class, *which is to be the same as its associated filename*, and a method within that class in curl brackets named `main()`

Every statement [line of code] in Java **ends with a semicolon (;)**, and any statement that doesn't end with a semicolon will crash the program

Side note: `System.out.print()` and `System.out.println()` are similar statements but do not output the same thing. The former merely prints onto the line the program's cursor is currently places, while the latter prints onto the line then creates a newline.

Java programs allow the user to **get input from the user** using `import java.util.Scanner`

A **scanner** is a text parser that is declared using `Scanner scnr = new Scanner(System.in);`, where `System.in` corresponds to keyboard input. This is then used to declared other variables with keyboard input: `int wage; wage = scnr.nextInt();`

The text within the double-quotes in `System.out.print("...")` (for example) is called a **string literal**
**To print variables**, the double-quotes are dropped from the construct so that you are calling the variable directly; failing to drop the double-quotes causes the line to print the variable name instead of the variable's content
Variables and strings can be **concatenated** into a single statement using the plus symbol (+): `System.out.println("You are " + user.age + " years old");`

**Comments** are text in a program that the program's compiler ignores, often used to convey the intent or purpose of a portion of the code. Or it could be used for overworked programmers to vent their frustrations about their management in a manner that won't get them fired. All valid uses!

**Single-line comments** begin with `//` and includes the following text on that line. They usually appear after a statement or before a portion of code.
**Multi-line comments** begin with `/*`, end with `*/`, and all the text between the two headers are part of the comment. These are also known as **block comments**.

**Whitespace** is the blank space between the left alignment of the workview and the text. It usually consists of 3 or 4 spaces, or a tab character. When a program is compiled, this whitespace is ignored, so its primary use is readability.

In programming, **every little detail counts.** Attention to detail is not negotiable.

There are a lot of different types of errors in programming. One of those types are **syntax errors** where a programming language's rules about how its symbols and expectations are violated. Even small stuff like a missing semicolon or parenthesis are violations.

When fixing errors, **focus on a single issue rather than the whole error message.** The other numerous errors could be a result of a single error.

There are **three notable kinds of errors**: compile time errors (errors detected during compiling), runtime errors (errors detecting while running), and logic (i.e. bugs, e.g. a wrong number).

There are also **warnings** which the compiler reports during its work, which won't prevent the program from being run, but may cause a runtime error.

### 2026-01-16
#### Textbook notes
The classic binary 0s and 1s are read by the computer where by the former are no voltage and the latter are positive voltage. These are also known as **bits**. Processors computer data, memory stores data (along with instructions).

Writing in binary is what's known as writing **machine instructions**, and a sequence of these instructions is called an executable.
Because the process of writing machine instructions is large and arduous, engineers began creating **assemblers** to translate human-readable code into machine-readable instructions. These are called **high-level languages**.
To correctly run programs using high-level languages, engineers created **compilers** to automatically translate language into executables.

Using this approach, executables can only be generated for a specific processor architecture, which requires the programmer to generate multiple executables for these architectures. Java uses an approach that allows a single executable to run on different processors.

A programmer needs to write, compile, and debug code. **Integrated development environments (IDEs)** allow this programmer to do all of it in a single application.

## Module 2
### 2026-01-21
#### Textbook notes
Honestly, anything I'm already familiar and practiced with, I won't be taking notes of. Seems very redundant. Basic concepts like variables and assignments don't need to be mindlessly reiterated so I can prove my intellectual worth.

