0x00. AirBnB clone - The console
Group project
Python
OOP
 By: Guillaume
 Weight: 5
 Project to be done in teams of 2 people (your team: Wangechi Agnes Gichuhi, Mfumu Mabunda)
 Project over - took place from Feb 6, 2023 6:00 AM to Feb 13, 2023 6:00 AM
 Manual QA review was done by on Feb 23, 2023 12:20 AM
 An auto review will be launched at the deadline
In a nutshell…
Contribution: 100.0%
Manual QA review: 0.0/48 mandatory
Auto QA review: 0.0/302 mandatory & 0.0/233 optional
Altogether:  0.0%
Mandatory: 0.0%
Optional: 0.0%
Contribution: 100.0%
Calculation:  100.0% * (0.0% + (0.0% * 0.0%) )  == 0.0%
Concepts
For this project, we expect you to look at these concepts:

Python packages
AirBnB clone


Background Context
Welcome to the AirBnB clone project!
Before starting, please read the AirBnB concept page.






First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine
What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Update attributes of an object
Destroy an object
