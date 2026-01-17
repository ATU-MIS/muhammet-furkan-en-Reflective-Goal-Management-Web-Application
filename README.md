# Reflective Goal Management System

This project presents the analysis and design of the Reflective Goal Management System, a web-based application aimed at helping users define personal goals, manage milestones, reflect on their experiences, and evaluate the accuracy of their time planning.

The repository focuses on software engineering analysis and UML-based system design rather than implementation. It was prepared for academic purposes within the scope of a software engineering or information systems course.

Project Overview

The Reflective Goal Management System enables users to log in securely, create and manage personal goals, divide goals into milestones, and associate learning resources with these milestones. Users can record reflective notes, attach supporting documents, and analyze the difference between estimated and actual time spent on goals. The system also provides visual feedback to help users understand their progress.

The primary objective of the project is to model system behavior and structure clearly using UML diagrams.

UML Diagrams

Use Case Scenarios
Use case scenarios describe the functional requirements of the system, including user authentication, goal creation and management, milestone tracking with learning links, note creation with file attachments, time reality checks, and system-driven feedback.

Class Diagram
The class diagram represents the static structure of the system and includes core domain entities and supporting services such as User, Session, Goal, Milestone, LearningResource, Note, Attachment, TimeRealityCheck, and ProgressVisualization.
The diagram was iteratively refined as system requirements evolved, while preserving the core domain model.

Sequence Diagram
A single end-to-end sequence diagram illustrates the dynamic behavior of the system. It demonstrates the interaction flow starting from user login, continuing with goal and milestone creation, note and attachment handling, time analysis and visualization, and ending with user logout.
The sequence diagram ensures consistency between use case scenarios and the class diagram.

Design Approach

The system design follows object-oriented principles and UML standards. A clear separation of concerns is maintained between user interface interactions, domain entities, service-level logic, and visualization components.
The design process reflects an iterative development approach, where initial models were improved based on detailed requirement analysis.

Tools Used

PlantUML was used for sequence diagram modeling. UML was used for use case and class diagrams. Documentation was prepared as plain text for clarity and academic presentation.

Academic Context

This project was developed as part of a university-level software engineering or information systems course. It demonstrates requirement analysis, UML modeling, and traceability between use case scenarios, class diagrams, and sequence diagrams.

Author

Furkan Şen

License

This project is intended for educational purposes only.
