# Flowcharts
## What is a Flowchart?
A flowchart is a type of diagram that visually represents a workflow or process using a set of symbols or icons to denote different actions/decisions/steps within the process with arrows showing the direction of the flow. Flowcharts are used across many different professions to help analyze, design, document, and/or manage a workflow or process.

## Why use a Flowchart?
Similarly to pseudo-code, flowcharts provide another way of approaching and/or understanding a workflow. Another benefit is that, when done well, flowcharts can be understood by non-developers and by developers that do not know the language the process is written in.

## Flowchart Symbols
This type of diagram is extremely versatile and is used across many professional fields. Due to the number of industries using flowcharts, many sets of symbols and styles have been created with a specific industry in mind. A good symbol set to use is the ISO 5807 symbol set, as they are well-known and often used in the technology industry.

## Some commonly used ISO 5807 symbols
Symbol			Name			Description

![image](https://user-images.githubusercontent.com/99530400/180783802-8ccc7501-7546-43c2-8416-2bfcc26d9d4b.png)

Flowline / Arrowhead	
Shows the order. Comes from one symbol to another

	
![image](https://user-images.githubusercontent.com/99530400/180783896-2a2e357a-6773-4a14-8691-8e3fe28bb0df.png)

Terminal / Terminator	
Shows where a process (or sub-process) starts or ends; text is usually “Start”, “Begin”, or “End”

	
![image](https://user-images.githubusercontent.com/99530400/180783982-f7de4ef2-0fc7-4825-809a-405b5b1311c4.png)

Process / Rectangle	
Process, action step, or operation; text is usually a verb, examples include: “Edit Video”, “Choose Plan”, “Set variable to ‘hello’”

	
![image](https://user-images.githubusercontent.com/99530400/180784129-1c31d709-de1f-46d0-bb8c-d5c4334f0809.png)

Data (I/O)	
Inputs to (entering data) and Outputs from (displaying results) a process

	
![image](https://user-images.githubusercontent.com/99530400/180784241-e0cb26c3-57a6-4d5d-942c-60bf02b26a25.png)

Decision / Conditional	
Used to ask a question whose answer determines the route taken from the question. Arrow from bottom is Yes / True, Arrow from side(s) is No / False, (Always label the arrows to make it clear)


![image](https://user-images.githubusercontent.com/99530400/180784315-7ebd7851-8f07-4dc4-bafa-60b189a9557b.png)

Document (s)
Represents a document or report


![image](https://user-images.githubusercontent.com/99530400/180784414-8a0d788a-6d84-4dbb-996d-239166720697.png)

Subroutine / Predefined Process	
A process that can be used in the current process but defined elsewhere (should have a separate flowchart for it)

	
![image](https://user-images.githubusercontent.com/99530400/180784481-6af38f5b-3586-402a-9a46-7ffeda72771b.png)

Annotation (Comment)
Additional info about a step; the line connecting to the step can be solid or dashed


![image](https://user-images.githubusercontent.com/99530400/180784555-ae548b0b-b663-43ca-af1a-809fd63ceae8.png)

On-page Connector
Replaces long or confusing lines, use a letter to reference

	
![image](https://user-images.githubusercontent.com/99530400/180784619-2246a635-048a-4227-a20c-23d5674d7b0b.png)

Off-page Connector	
To connect this process to the next step, which is on another page; use page number for reference


![image](https://user-images.githubusercontent.com/99530400/180784661-6070f593-60d1-4a00-a504-dfd3a941e666.png)

Data File / Database
Data represented by a cylinder (originally representative of disk drive)


# An Example
Let’s think about Foundation task, and include a flowchart example for it:

The task instructions are as follows:

Write a function that draws a straight line in the terminal.

  * Prototype: `void print_line(int n)`;
  * You can only use `_putchar` function to print
  * Where `n` is the number of times the character `_ `should be printed
  * The line should end with a `\n`
  * If `n` is 0 or less, the function should only print `\n`
Take a moment to write out a solution in pseudo-code.





…



No, really. It’s good practice. :)



…



Okay. Below is what I came up with.

Set a variable equal `n` (`int nCopy`)
Set up a while loop (condition: `nCopy` is greater than 0)
Print `-`
Decrease `nCopy` by 1
Print `\n`

Now, using the ISO 5807 symbols from the table above, draw out a flowchart for this function.



…



No peeking!



…




Alright, does your flowchart look similar to the diagram below?

![image](https://user-images.githubusercontent.com/99530400/180785466-3e6afa19-fd5d-4606-9bd7-4c3e423da6e9.png)


# Bonus Info
Some good uses of flowcharts:

  * Create a flowchart before coding a task to either help create or validate pseudo-code
  * Add to a README.md to visually show how your project/process works
  * Use in a presentation to aide audience understanding
  * Your function or process is not working as expected? Create a flowchart of how it CURRENTLY is. Then, walk through the chart with some example input.
A flowchart can be as high-level or as detailed as you want. For example, you could break the flowchart above down further to include what is happening in memory. You can even create flowcharts from your everyday non-technical experiences. Choosing a movie or a place to eat could be displayed as a flow-chart!

A helpful tool to create flowcharts is [draw.io](https://alx-intranet.hbtn.io/rltoken/aOmwlxIhyIzTDorIC5SNWA). There are premade symbols for you to use and your diagrams can be saved to your Google Drive.

For more information on Flowcharts and related diagrams, a google search with simply “flowchart” can get you started. ;)

