Community Lost & Found Matching Network

Name: Divyanshu Jha
SRN: PES2UG24CS915

About the Project

This project is a Community Lost & Found Matching Network. The main idea is to help people report things that they have lost or found and help them find possible matches.

The system also has features for notifications, ownership verification and managing reports.

Labs Included

This repository contains the work done for Lab 1, Lab 2 and Lab 3.

Lab 1 – Requirements Engineering & UML

In Lab 1, I worked on the requirements of the Community Lost & Found system.

The main things included are:

Functional requirements

Non-functional requirements

UML use-case diagram

Use-case flow for verifying ownership and claiming a found item

Some of the main system functions are:

Report Lost/Found Item

Search and Match Items

Receive Match Notification

Verify Ownership

Claim/Request Handover

Manage Reports

The use-case flow also contains a main success scenario and an alternate flow for an incorrect security answer.

Lab 2 – Agile Backlog & Sprint Simulation

In Lab 2, the requirements were converted into Agile backlog items.

The backlog contains user stories such as:

Report Lost Item

View Lost Items

Report Found Item

View Found Items

Search and Filter Items

Match Similar Items

Receive Match Notifications

Review Item Reports

Manage Item Categories

Remove Invalid Reports

Story points were given to the user stories and they were divided into two sprints.

A burndown chart was also prepared to show the remaining work during the sprint.

Lab 3 – Component Modelling & Architecture

In Lab 3, I converted the system requirements into a component-level design.

I selected Layered Architecture for the system.

The main layers are:

Presentation Layer

Business Layer

Data Layer

The main components used are:

User Interface

Search & View

Admin Interface

Lost & Found Manager

Matching Service

Notification Service

Database

The components communicate using interfaces such as the Item Report Interface, Matching API, Notification API and database queries.

Repository Structure

Community-Lost-and-Found/
│
├── Lab1/
│   ├── Requirements
│   ├── UML Use-Case Diagram
│   └── Use-Case Flow
│
├── Lab2/
│   ├── Sprint Backlog
│   ├── Sprint Summary
│   └── Burndown Chart
│
└── Lab3/
    ├── Component Diagram
    └── Architecture Justification

Main Requirements

Some important requirements of the system are:

The system should match found items with lost item reports using details such as category, color and location.

Users should be able to create lost and found item reports.

Potential owners should receive notifications when a suitable match is found.

Ownership should be verified before handover details are revealed.

The Community Admin should be able to review, remove or flag suspicious reports.

Architecture Choice

For Lab 3, I selected Layered Architecture because it gives a simple separation between the user interface, business logic and database.

This also makes the project easier to understand and maintain.

Tools Used

Jira – for Agile backlog and sprint simulation

UML – for modelling the system

Draw.io / diagram tools – for diagrams

Microsoft Word / PDF – for documentation

Excel – for requirements and backlog tables

Conclusion

Through these three labs, the Community Lost & Found system was developed step by step.

Lab 1 focused on what the system should do.

Lab 2 focused on planning the work using Agile/Scrum.

Lab 3 focused on how the system can be divided into components and organized using an architecture.
