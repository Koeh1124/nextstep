# NexStep

## Table of Contents

| Seciton Name | Overview Link | Documentation Link |
| --- | --- | --- |
| Overview | [link](#Overview) | This file |
| Modules | [link](#Modules) | [MODULES.md](./Modules/MODULES.md) |
| Students | [link](#Students) | [STUDENTS.md](./Students/STUDENTS.md) |
| Workflow | [link](#Workflow) | [WORKFLOW.md](./Workflow/WORKFLOW.md) |

## Overvieow

### Purpose

The main purpose of this project is to allow students to have acess to courses/modules that will allow them to learn any place, any time, and at their own pace.

The seocundary goal is to expand the Catapult program.
This is built as a sister program to Catapult, expanding the reach of Nextech and providing valuable resources to students further than the Catapult program is built to handle.
Students will be able to learn and grow ther skills both pre and post Catapult, or even without ever participatiing in Catapult.

## Modules

Each modlue is in one of three categories

1. [Languages](./Modules/language_modules/LANGUAGES.md)
2. [Topics](./Modules/topic_modules/TOPICS.md)
3. [Projects](./Modules/project_modules/PROJECTS.md)

Ecah of these module types have their own section in this documentation goes over the general structure that a module should follow, current modlues that exits for that category, and a backlog of modules.

### General purpose of each module type

Languages:

These are meant to introduce the students to a programming language.
Showing them how to do things like define a variable, define a function, make an object, import a library, etc.
These should be made to be ever expanding as each language will always be changing and expanding as well.
Along with the language itself, these modules may also have portions that will cover popular libraies and tools in that language.
These tool may also be built into more full modules in the Topic category for the modules.
For example in a python language module there may be a section focusing on numpy or the typing module, but those more than likely would be kept to just that section.
But a libray like Pandas or Flask would be made into their own toic libray as they are so big and used to do very specific tasks in python (data science and writing APIs/websites)

Topics:

These are built out to cover a specific topic such as APIs, data structurs and algorithms, data science, etc.
Think of these like a CS class, they won't introduce you to a language but rather how to use that language to solve specific problems.
These modules will also have multiple versions of them covering the same material, but in diffrent languages.
This will allow the students to go through the content in the language that they are most comfterable with.
This does depend on the language also of course, we can't have a module covering object-oriented programming in C because C does not have objects.

Projects:

As the name suggests these are projects that the students can make and show off on a portfolio or resume.
These are the what the language and topic modules come together to make.
Of couse a student can complete these without doing the language and topic modules as the modules can all be done in whatever order the student wants to do.
However, there will be a list of suggested modules that the student completes before doing the project as the project will rely on the material those modles contain.
It's good practice to build out any prerequisite modules before building out the project that relies on them to make it easier on students.

### Current and WIP Modules

List of modules that are either currently released or are currently being worked on (repo and beta branch avalible)

| Module name | Module Type | Language | State | Link |
| ----------- | ----------- | -------- | ----- | ---- |
| JavaScript | Language | JavaScript | WIP | TBA |
| Data Structures and Algorithms | Topic | JavaScript | WIP | TBA |
| API Project | Project | JavaScript | Project | WIP | TBA |

### Planned Modles and Expansions

List of modules that are planned or in the backlogue, these may or may not have an exisiting private repo/branch

| Module name | Module Type | Language | New or Expansion |
| ----------- | ----------- | -------- | ----- |
| Python | Language | Python | New |
| Data Structure and Algorithms | Topic | Python | Expansion |
| Calculator Project | Project | Python | New |
| API | Topic | JavaScript/Python | New |
| API Project | Project | Python | Expansion |

## Students

Students and the student experiance should be our first, secound, and third priority.
Taking down barriers to education of these topics is vidal to Nextech's goal of giving every student the oppritunity of experiancing the world of tech.
Documenting the student experiance is as important as the content of this project itself.
Without knowing how students interact with the material we will never know how to improve the material.
One of the biggest driving forces for most of the project design is constant innovation and improvement.
This is not only to keep up with the ever evolving world of tech but also to keep up with the ever evolving perception the students have of topics in tech.

### Student Access



### Student Feedback



### Ideal Student Experiance



## Workflow

General guideline for how the workflow for each given module should look like.
Having a section to document this closely will make creating new modles and expansions go smoothly.
This will also make it easy to add extra people to the project as this is designed to be highly parralelized and contained between modules.
Desigining the workflow of the project this way should reduce the need for meetings, allowing people to put more time into perfecting the modules and creating the best student experiance as possible.

### Moudle Templates

There should be templates made for every level of each module.
One for a gereneral module in a specific language, one for the specific type of module, one for the specific module itself.
The gerneral module template will have information about diffrent testing methods, what works, what dosen't, why certian descions were made etc.
The main purpose of this is to reduce friction when writing a new module in that language, weather it be a brand new modle or an expansion of an existing module.
Having a template for each diffrent type of module ( Language, Topic, Project ) will allow making new modules of that type easier.
We can document about how much time each level of the module should take, best practices for introducing students to that type of material, and more general guidlines to make sure all modules are cohesive.
The Major goal with this type of template is to make the modules have the same level of relative difficulty and have gernerally the same vibe.
Having a template for each diffrent topic and project will allow translation between languages to be easier.
Doing this will make sure we cover the content in a similar order and have examples and test cases be around the same level as a module covering the same topic in a diffrent language.
This is meant to make the student experiance better as one student will not feel like they are being punished by doing a topic in Java rather than doing it in Python.

** We should also add a template for templates here :D **

### Planning MOdules



### Writing Modules



### Moudle Release/Staging



### Plannig Expansions



### Writing Expansions



### Expansion Release/Staging



### Documentation



### Bug Reporting



### Matianace


