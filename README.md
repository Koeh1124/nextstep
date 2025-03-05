# NexStep

## Table of Contents

| Seciton Name | Overview Link | Documentation Link |
| --- | --- | --- |
| Overview | [link](#Overview) | This file |
| Modules | [link](#Modules) | [MODULES.md](./Modules/MODULES.md) |
| Students | [link](#Students) | [STUDENTS.md](./Students/STUDENTS.md) |
| Workflow | [link](#Workflow) | [WORKFLOW.md](./Workflow/WORKFLOW.md) |

## Overview

### Purpose

The main purpose of this project is to allow students to have access to courses/modules that will allow them to learn any place, any time, and at their own pace.

The secondary goal is to expand the Catapult program.
This is built as a sister program to Catapult, expanding the reach of Nextech and providing valuable resources to students further than the Catapult program is built to handle.
Students will be able to learn and grow their skills both pre and post Catapult, or even without ever participating in Catapult.

## Modules

Each module is in one of three categories

1. [Languages](./Modules/language_modules/LANGUAGES.md)
2. [Topics](./Modules/topic_modules/TOPICS.md)
3. [Projects](./Modules/project_modules/PROJECTS.md)

Each of these module types have their own section in this documentation goes over the general structure that a module should follow, current modules that exits for that category, and a backlog of modules.

### General purpose of each module type

Languages:

These are meant to introduce the students to a programming language.
Showing them how to do things like define a variable, define a function, make an object, import a library, etc.
These should be made to be ever expanding as each language will always be changing and expanding as well.
Along with the language itself, these modules may also have portions that will cover popular libraries and tools in that language.
These tool may also be built into more full modules in the Topic category for the modules.
For example in a python language module there may be a section focusing on numpy or the typing module, but those more than likely would be kept to just that section.
But a library like Pandas or Flask would be made into their own topic library as they are so big and used to do very specific tasks in python (data science and writing APIs/websites)

Topics:

These are built out to cover a specific topic such as APIs, data structures and algorithms, data science, etc.
Think of these like a CS class, they won't introduce you to a language but rather how to use that language to solve specific problems.
These modules will also have multiple versions of them covering the same material, but in different languages.
This will allow the students to go through the content in the language that they are most conferable with.
This does depend on the language also of course, we can't have a module covering object-oriented programming in C because C does not have objects.

Projects:

As the name suggests these are projects that the students can make and show off on a portfolio or resume.
These are the what the language and topic modules come together to make.
Of course a student can complete these without doing the language and topic modules as the modules can all be done in whatever order the student wants to do.
However, there will be a list of suggested modules that the student completes before doing the project as the project will rely on the material those modules contain.
It's good practice to build out any prerequisite modules before building out the project that relies on them to make it easier on students.

### Current and WIP Modules

List of modules that are either currently released or are currently being worked on (repo and beta branch available)

| Module name | Module Type | Language | State | Link |
| ----------- | ----------- | -------- | ----- | ---- |
| JavaScript | Language | JavaScript | WIP | TBA |
| Data Structures and Algorithms | Topic | JavaScript | WIP | TBA |
| API Project | Project | JavaScript | WIP | TBA |

### Planned Modules and Expansions

List of modules that are planned or in the backlog, these may or may not have an existing private repo/branch

| Module name | Module Type | Language | New or Expansion |
| ----------- | ----------- | -------- | ----- |
| Python | Language | Python | New |
| Data Structure and Algorithms | Topic | Python | Expansion |
| Calculator Project | Project | Python | New |
| API | Topic | JavaScript/Python | New |
| API Project | Project | Python | Expansion |

## Students

Students and the student experience should be our first, second, and third priority.
Taking down barriers to education of these topics is vital to Nextech's goal of giving every student the opportunity of experiencing the world of tech.
Documenting the student experience is as important as the content of this project itself.
Without knowing how students interact with the material we will never know how to improve the material.
One of the biggest driving forces for most of the project design is constant innovation and improvement.
This is not only to keep up with the ever evolving world of tech but also to keep up with the ever evolving perception the students have of topics in tech.

### Student Access

Students will have access through a public GitHub project.
This project will have a repo for each of the different modules.
If a module is available in multiple languages, those will be available on different branches of that repo.
This would ensure that students will have access to the repos anywhere and at anytime (as long as GitHub is online when they pull down the repo).
Of course the student would not be able to push to the repo, but if they want they can for the repo and push the code to their own git repo.
All necessary commands and explanation for how to pull code and such will be linked to in each of these projects.

### Student Feedback

Student feedback can be taken via forms that will be linked to in each lesson.
These will include thins like:

- Which lesson they are taking the survey about
- How useful they thought the lesson was
- How do they think that we could improve on each lesson
- What additions would they like to see
- If they have any ideas for future lessons
- Was there anything that they though was unclear about the lesson

These lessons may also potentially be tested on the Catapults, taking a day to run through a lesson and provide feedback.
This will allow us to get quick feedback in real-time, which would be very useful.

### Ideal Student Experience

Ideally the students will have all that they would need to do the lessons available to them in the lesson's documentation.
However, this of course will not be the case.
As much as we try students will always ask questions that we will not be able to account for.
Hopefully through these questions the students can learn additional skills like how to properly search for information.

Student's should be able to use both the documentation/instructions plus searching for information on the internet to complete any of the lessons on their own.
Some lessons will be harder than others of course.
We will have a difficulty rating and a list of lessons that the students are recommend to take before attempting the given lesson.
These lessons will be built to all build on each other and slowly increase in difficulty until the students reach a project.

## Workflow

General guideline for how the workflow for each given module should look like.
Having a section to document this closely will make creating new modules and expansions go smoothly.
This will also make it easy to add extra people to the project as this is designed to be highly parallelized and contained between modules.
Designing the workflow of the project this way should reduce the need for meetings, allowing people to put more time into perfecting the modules and creating the best student experience as possible.

### Module Templates

There should be templates made for every level of each module.
One for a general module in a specific language, one for the specific type of module, one for the specific module itself.
The general module template will have information about different testing methods, what works, what doesn't, why certain decisions were made etc.
The main purpose of this is to reduce friction when writing a new module in that language, weather it be a brand new module or an expansion of an existing module.
Having a template for each different type of module ( Language, Topic, Project ) will allow making new modules of that type easier.
We can document about how much time each level of the module should take, best practices for introducing students to that type of material, and more general guidelines to make sure all modules are cohesive.
The Major goal with this type of template is to make the modules have the same level of relative difficulty and have generally the same vibe.
Having a template for each different topic and project will allow translation between languages to be easier.
Doing this will make sure we cover the content in a similar order and have examples and test cases be around the same level as a module covering the same topic in a different language.
This is meant to make the student experience better as one student will not feel like they are being punished by doing a topic in Java rather than doing it in Python.

** We should also add a template for templates here :D **

### Planning Modules



### Writing Modules



### Module Release/Staging



### Planning Expansions



### Writing Expansions



### Expansion Release/Staging



### Documentation



### Bug Reporting



### Machinate


