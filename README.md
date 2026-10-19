# CS-255: System Analysis and Design
**Southern New Hampshire University**  
**Student:** Rolfe H. Green

## REPOSITORY OVERVIEW

This repository supports coursework for CS-255: System Analysis and Design.

The course covers business requirements, system design, UML modeling, and communication with stakeholders.

## REPOSITORY CONTENTS

This repository contains course assignments, system design documentation, UML diagrams, and supporting technical resources for the DriverPass project.

- Business Requirements Document (Project One)
- System Design Document (Project Two)
- UML diagrams (use case, activity, and sequence)

## CS 255 – DriverPass Project Reflection

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
The DriverPass project was a system-analysis and design effort for a driving school client. The client needed a web-based system that would let students register and manage profiles, select training packages, book or change driving lessons, take online classes and practice tests, and view progress. Staff roles (secretary, drivers, IT officer, and owner) needed tools to manage schedules, record lesson notes, maintain an audit trail, enable or disable packages, and receive DMV updates. The system was designed as a multi-actor web application centered on scheduling, progress tracking, and compliance.

### What did you do particularly well?
I produced a complete set of UML diagrams (use-case, activity, and sequence) that made the main flows—especially lesson scheduling and practice-test progress—explicit and traceable. The sequence diagram for reserving a two-hour lesson clearly showed the interactions among the web interface, scheduling service, database, and notification service, including the alternate path when no eligible slot remained. Keeping the business rules (remaining hours, availability checks, and audit trail) visible in the diagrams was a strength.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would revise the system design document’s section on non-functional requirements and testability. While the functional flows are well covered, I would add more concrete performance, security, and audit-retention criteria, plus explicit test scenarios tied to each major use case. This would make the document more useful to the implementation and maintenance teams later.

### How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
I started from the actors and their goals (student wants to book a lesson and see progress; secretary wants to manage accounts and schedules; owner wants audit and package control). Those needs became the use cases, which then drove the activity and sequence diagrams. Considering user needs is essential because a technically correct system that does not match how people actually work will be unused or will create workarounds, increasing maintenance cost and risk.

### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
I begin with stakeholder interviews and use-case identification, then move to activity and sequence diagrams to clarify flows and dependencies before writing detailed design. In the future I would also add earlier prototyping of critical screens, a short risk-and-assumptions log, and explicit non-goals so that scope stays controlled. Pairing the design documents with a living backlog of open questions would further improve hand-off to implementation.

## GENERATIVE AI DISCLOSURE

Where generative AI assistance is used, its role will be acknowledged in the relevant assignment or documentation, consistent with course requirements.

## ACADEMIC PURPOSE

This repository is maintained for educational purposes at Southern New Hampshire University.
