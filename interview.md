# Interview project

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

This language would serve geologists and geology students, and would help them to calculate the depths of reservoirs and sediment layers. 

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

Geologists who are looking to find oil or rare minerals need to be able to calculate the depth of sediment layers. They currently use languages like R to do so, but they are not very intuitive and difficult to use for geologists who aren't used to programming. 

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

A language that concentrates specifically on making these calculations could have a much simpler syntax compared to R and be easier to learn for geologists. 

### Why you?

_What excites you about this idea? How did you come up with it?_

I am not a geologist, but these tasks that the language would be used for seem exciting to me. I would love to be able to help out geologists by making their work a little easier. 

### Domain

_Describe the project's domain in five words._

Calculating sediment and reservoir depths

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The language should include functions that handle the various calculations for determining the depths of sediment layers and reservoirs. It should not require the use of any variables or advanced programming techniques. It should just be able to make simple calculations. 

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

If the program runs correctly, it should return the various depths in a print statement that is easy to understand or in a graph specified by the user. If there are any error the language should specify which parameter is causing the error. 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to calculate equations and generate graphs for geological purposes, but it should be hard to generate anything else with it. It should be impossible to code anything that could be used outside of geology because that would make it more confusing for geologists to learn. 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I was able to find [this article](https://www.sciencedirect.com/science/article/pii/0098300492900959) which describes a spreadsheet routine that can be used for the same purposes as this DSL. It includes a lot of helpful functions to easily calculate sediment depths, but I could see this being confusing for people who are not experts at spreadsheets. I couldn't find any examples of DSLs do this, so there currently isn't any options for a simpler method for those who prefer programming. My roomate who is a geology major said they currently use R for this and he found it to be pretty hard to learn and wishes it could be simpler. 

## The Project

This section examines whether the idea makes for a good CS 111 project.

I think it would be a good project but probably not for me. I know almost nothing about geology and would need to take a lot of time to learn the language that I would rather spend designing my DSL. 

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I would think that someone would spend equal time on both design and systems since they are both important to this language. The design must be imple and easy to understand for the language to be valuable to geologists, but it is also important that the functions actually work. 

### Scope

_How big an idea is this? How ambitious is this project?_

I feel like this idea is relatively small, although I do not know much about geology. It is such a specific domin that I don't think there would really be that much to cover, and a lot of time could be spent on the finer details. 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

This DSL would be very helpful for geologists and make their work more efficient, but I could also see this language potentially used for purposes that have a negative environmental impact such as mining. 
