## Chapter 1: Intro
* If you can visualize a system you can probably implement it in a computer program. It is the purest creative activity.
Eliminating Complexity
1. Make code simpler and more obvious
2. Encapsulate complexity so that other people can work on your system without needing to know how it works. (modular design, encapsulation)

* Waterfall model - divide project into phases that needs to be complete before other phase.
* Agile model - iterate your design so that each iteration exposes problems and fixes the existing design.

Agile is more popular because software you will run into problems and you cannot know the whole design and issues that will pop up. So just starting to implement and changing as development happens is usually better and more flexible.

## Chapter 2: Nature of Complexity
* The ability to recognize complexity is a crucial design skill. It allows you to identify problems before you invest alot of effort in them. You can then think of alternatives and compare the complexity of each.
* Complexity = anything that makes the software hard to understand or modify the system
  * Complexity is easier to see from reader vs creator. -> ask others to review your design

**Symptoms of Complexity**
- Simple changes require code modifications in many different places
- Dev needs to know how different modules work to make a change. Instead of it just works
- Its not obvious certain modules need to be modified to complete the task you want to do. (tribal knowledge)

**Cause of Complexity**
Dependencies
- Exists when a piece of code cannot be understood and modified in isolation
- it is a fundamental part of software and cannot be eliminated. Thats why we have to think around it and design purposefully
- Leads to change amplification and high cognitive load
Obscurity
- Important info is not obvious
- unknown unknowns - contribute to high cognitive load

Complexity is incremental
- Complexity isn't caused by a single error - it accumulates in lots of small chunks
- Incremental nature makes it hard to control
