---
permalink: /about/
title: About the course
---
## {{ site.data.course.quarter }}

  - **Lectures:** {{ site.data.course.lecture_schedule }}
  - **Labs**: {{ site.data.course.lab_schedule }}
  - **Lecturers**: {{ site.data.course.instructors | map: "name" | join: ", " }}
  - **CAs**: {{ site.data.course.cas | map: "name" | join: ", " }}
  - **SLs**: {{ site.data.course.sls | map: "name" | join: ", " }}


{% include gallery.html %}

CS107 is the third course in the systems core sequence.
The CS106A/B courses provide students with a solid foundation in programming methodology and abstractions, and CS107 follows on to develop the skills needed to build computer systems. 

__CS107e: Computer Systems from the Ground Up__ is a variant of CS107 that teaches the fundamental concepts of
computer systems through bare metal programming on the Raspberry Pi. Bare metal
programming means you will not run an operating system on the Raspberry Pi and
will make minimal use of libraries. This course also serves as an
introduction to embedded systems. The course starts with the microprocessor and moves up to
the C programming language, without skipping anything in between. The goal is
to build a solid understanding of all aspects of how modern computers execute
programs and how program development tools work.

The major learning goals for the course are:

1. To understand how computers represent information, execute programs, and control peripherals.
2. To master command-line programming tools and the C programming language.

Topics covered include:

  -   the ARM architecture
  -   assembly language and machine-level code
  -   the C programming language
  -   compilation, linking and loading
  -   debugging
  -   memory organization and management
  -   controlling peripherals: GPIO, graphics, sound, and keyboards

Students will receive a Raspberry Pi and a kit of parts,
and all assignments will run on the Raspberry Pi. Assignments build upon each other by adding more and more functionality to a core library.
They culminate in a simple personal computer shell
using a keyboard and display. Finally, students do a project of their choosing 
where they build a complete hardware-software system.

This class is organized by weeks. Each week has lectures
on Fri and Mon, a 2-hour lab session midweek, and a programming
assignment which is due the following week. Lecture and lab attendance is mandatory. The final project is completed over the last two weeks of the quarter. There are no exams.

For information about the differences between CS107 and CS107e,
check out this [FAQ](https://web.stanford.edu/class/cs107e/).

## History
CS107e is a new approach to introducing students to computer systems in the Stanford curriculum. It is the brainchild of __Pat Hanrahan__; the course owes its very existence to Pat's inspiration and travail, along with the heroic contributions of the multi-talented __Isabel Bush__, the Lead TA in the first offerings of the course. __Phil Levis__, __Dawson Engler__, __Julie Zelenski__, and __Chris Gregg__ have contributed to the cause as instructors and we've have enjoyed superb student collaborators: __Anna__, __Ashwin__, __Eric__, __Jane__, __Jennifer__, __Lenny__, __Liana__, __Maria Paula__, __Michelle__, __Mihir__, __Ngoc__, __Omar__, __Peter__, __Sean__, __Sergio__, __Shannon__ and __Will__. The tireless efforts of the TAs to support student learning have earned boundless praise from our students.
A huge shout-out to __David Welch__, the person most
responsible for figuring out how to write bare metal programs on the Raspberry
Pi. If it weren't for the [great work of David shares](https://github.com/dwelch67/raspberrypi), we would not be offering this course!

Our course materials have evolved to a fairly solid and stable state. We would be delighted for others to adopt from our work. Contact us at `cs107e@cs.stanford.edu` for more information and access to our private-facing material.

