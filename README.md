# System Design Preperation

This repo contains system design of different applications and services.

 - [Bitly - URL Shortener](./Bitly/bitly.md)

## How to approach any system design problem

![Approach Diagram](./Diagrams/approach.svg)

1. ### Gather Requirements
    - Functional Requirements (eg - users can post tweet, users can comment, etc)
    - Non - Functional Requirements (eg -scalablility, consistency, availability, etc)

2. ### Design Core Entities
    - Design models or classes (eg - user, vehicle, etc)
    - Define relationships (eg - one user can have many tweets, etc)

3. ### Design API
    - Design only main APIs (eg - posting a tweet, etc)

4. ### Data Flow (optional based on application)

5. ### High Level Design
    - Design how your user can talk to backend, how does your application talk to database, etc

6. ### Deep Dive
    - Explain the concepts and decisions related to APIs
    - Explain how to achieve non functional requirements

## Extra Tips 
- Always ask questions regarding the application to the interviewer.
- Always think of CAP theorem when listing non - functional requirements.
- You can ask interviewer how much scaling are we expecting or how much users and all info. He can either tell you exact numbers or ask to estimate the numbers.
- Don't get stuck in deep dives of API's. Always complete all the phases of system design first, then go deep dive.