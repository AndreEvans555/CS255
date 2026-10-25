# CS 255: System Analysis and Design
## DriverPass Portfolio — Andre Evans

This repository contains my DriverPass portfolio artifacts for CS 255. The projects show how I translated a client's needs into business requirements and a proposed system design.

## Portfolio Documents

- [Project One: Business Requirements Document](Andre_Evans_CS255_Project_One_Business_Requirements.docx)
- [Project Two: System Design Document](Andre_Evans_CS255_Project_Two_System_Design.docx)

## Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client was DriverPass, a driver-training business represented by its owner, Liam, and IT officer, Ian. They wanted a web-based system that would help customers prepare for their DMV driving tests through driving lessons, online learning, and practice tests. The system needed to support customer registration, training packages, lesson reservations, and progress tracking. It also needed to give staff tools to manage schedules, accounts, reports, and access permissions. My work included documenting these requirements and creating UML diagrams and technical recommendations for the design.

## What did you do particularly well?

I think I did well connecting the client's requests to specific system requirements. For example, I broke scheduling into rules for two-hour lessons, remaining package hours, and the availability of the student, driver, and car. I carried those rules into the booking workflow and included a final availability check to help prevent double-booking. I also separated confirmed requirements from proposed features and decisions that still needed client approval. This helped make the design more realistic without treating every assumption as something the client had requested.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the reservation workflow to explain cancellation and error handling in more detail. The design identifies cancellation and hour-restoration policies as open decisions, so I would first confirm those rules with the client. Then I would expand the activity and sequence diagrams to show what happens when someone cancels, a time slot becomes unavailable, or a reservation cannot be saved. I would also check that the same rules and terms appear consistently in the requirements, diagrams, and acceptance criteria.

## How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?

I reviewed the DriverPass interview and considered what each type of user needed to accomplish. Customers needed access to lessons and learning materials, the secretary needed to assist customers with registration and scheduling, and management needed reports and account controls. I translated those needs into functional requirements, role-based access, and UML models. For example, customers could book their own lessons, while the secretary could make reservations for people who called or visited. Considering user needs matters because a system can work technically and still fail to solve the customer's actual problem.

## How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I approach software design by understanding the problem before choosing the technology. I identify the users, gather requirements, separate required features from assumptions, and break larger processes into smaller steps. For future projects, I would continue using interviews, use cases, activity diagrams, sequence diagrams, and class diagrams. I would also use simple prototypes and regular client feedback to check my understanding early. A requirements traceability table would help me connect each requirement to a design element and a test so that important needs are not missed.

