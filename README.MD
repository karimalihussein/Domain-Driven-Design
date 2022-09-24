# Domain Driven Design
This is a collection of notes on Domain Driven Design. It is a work in progress and will be updated as I learn more.

# What is Domain Driven Design?
DDD is an approach to software development that focuses on the core domain and domain logic of an application. It is a way of thinking about software development that is based on the following principles:

for example: 

* Clinic Management System: 
    * Patient
    * Doctor
    * Appointment
    * Prescription
    * Invoice
    * Local Payment
    * Insurance Payment
    * Reports
    * etc.
the above are the core domain of the system, you will be able to build the system based on the above domain clearly and easily without any confusion and when you know more about the domain you will be able to add more features to the system easily.

# The Need for Domain Driven Design (DDD)

* Clients don't care about the technology you use to build their software, they care about the business value that the software provides.
* Clients Care About their Problems, which might be changeable and how your software solves their problems.
* Domain Driven Design helps in mangemnet of complexity business logic.
* Lack of Code Organization and Reusability.
* the client might change the requirements of the system and you will have to change the code to fit the new requirements.

- Complex Business Applications
 * Long Life Span 
 * Continuous Business Change
 * Continuous Maintenance
 * Changes should have minimal impact to the rest of the system
 * Multiple Stakeholders

 # The Benefits of Domain Driven Design (DDD)
 1 - it helps the team create a common language between the team members about the business requirements, data entities, and business logic.

2 - the created model is modular, extensible, and reusable. and easy to maintain. design reflects the business domain.

3 - it improves the readability of the code and the code is easy to understand.

4 - DDD is not rules or a framework, it is a way of thinking about software development (Guidelines).

# Strategic Patterns of Domain Driven Design (DDD)
- Distilling The Problem Domain To Reveals What is important
- Creating an abstract version of the requirements
- Creating a Model to solve Domain Problems
- Define key problems and create a solution to suit domain problem separately
- usning a chared language to enable modeling collaboration
- create a common definition of the domain model
- isolate models form ambiguity and corruption

for example:
 the system has problems, you need to saparate the problems into different parts and solve each part separately and then combine them together to solve the whole problem, this is called strategic patterns, and it is the first step in DDD.

 don't try to solve the whole problem at once, try to solve the problem in parts and then combine them together to solve the whole problem.

 # Ubiquitous Language
 - Considered at the first step of any project
   - Always start with knowing the domain and your clients
 - Vacabulary of domain-specific terms
   - nouns, verbs, adjectives, adverbs, idiomatic expressions and even advebs
 - Shared by all parties involved in the project
   - Primary goal of avoiding misundertanding
 - Used in all forms of spoken and written communication
   - Domain Model
   - Code
   - Documentation
   - Meetings
   - Emails
   - etc.
 - comes out of interviews with the client and the team

  


