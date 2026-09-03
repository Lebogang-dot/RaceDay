RaceDay System

RaceDay is an event management system designed to manage running, walking and cycling events. The system provides two main user roles: Organiser and Participant.

Organiser

Organisers can create, update and delete events. They can also create event categories, view participant enrolments and record participant results after an event.

Participant

Participants can register and log in, manage their own profile, view available events and categories, enter events and view their own results.

Database

The database consists of seven main entities:

Users
Organisers
Participants
Events
Categories
Enrollments
Results

The database uses primary and foreign keys to maintain relationships between entities and constraints to maintain data integrity.

API

The RaceDay API provides endpoints for authentication, profiles, events, categories, enrolments and results. Swagger is integrated into the API so that endpoints can be viewed and tested through a web browser.

CI/CD

GitHub Actions is used to automatically validate that the required documentation files are present in the /docs folder.
