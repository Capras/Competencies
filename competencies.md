

### 1. FRONT END DEVELOPMENT HTML & CSS

---

##### Personal proof of concept for HTML & CSS Including Bootstrap:
This is a simple, responsive website from July 2017 that uses HTML, CSS, and Bootstrap.

[Basic Business Website - hosted](https://krystin987.github.io/maggie/)

[Basic Business Website repository](https://github.com/krystin987/maggie)

This basic outline for creating a simple 'first web app' boilerplate was developed in January 2018 for incoming apprentices. It briefly describes the three basic file components (html, css, javascript) and how to write them to see immediate results in a browser.

[Basic File boilerplate repository](https://github.com/krystin987/Boilerplate)

---

- [ ] Solid Knowledge of common tag types and how to implement them

      Document Structure

      Content Tags

      Semantic Tags - introduced in HTML5 - designed to indicate function of content blocks

      Empty Tags

      Tables


- [ ] Understands how the browser handles conflicting styles


- [ ] Understands how the DOM is laid out and is structured


- [ ] Understands the difference between content & styling


- [ ] Understands that different browsers render and interpret things slightly differently and the need to test on commonly used platforms

##### Bootstrap

- [ ] Knowledge of Bootstrap properties and design principles


- [ ] Understands grid concept & how to manipulate it


- [ ] Can install either by CDN or local file




### 2. MIDDLEWARE DEVELOPMENT

---

##### Personal proof of concept for Middleware Development including JavaScript, AJAX, HTTP, & jQuery:
The library project from July 2017 uses object oriented programming, prototypical modeling, JQuery, and JSON objects.

[Library Project - hosted](https://krystin987.github.io/Library-Project/)

[Library Project repository](https://github.com/krystin987/Library-Project)

The HTML5 "Brickout" Canvas Game from January 2017 uses object oriented programming, prototypical modeling, JQuery, HTML5 canvas, object collision, webpack deployment, and test driven development.

[HTML5 "Brickout" Canvas Game - hosted](https://krystin987.github.io/game-time/)

[HTML5 "Brickout" Canvas Game repository](https://github.com/krystin987/game-time)

---

- [ ] **JavaScript**

- [ ] Solid understanding of HTML & CSS


- [ ] Understanding of browser runtime & where to inject scripts


- [ ] Understanding of dynamic typing and how it makes using the language quick and easy - *more concise, better for runtime debugging in the console, more suited to prototyping*


- [ ] Understanding of Document Object Model


- [ ] Knowledge of JSON and working with JSON objects


- [ ] Knowledge on how to traverse the DOM for element handles


- [ ] Know how to structure native JavaScript classes (OOP, Pub/Sub) using prototype or object literal statements - *See 4 ways of creating objects in JS:*


##### AJAX

---

The Zayo Route Visualization project from Fall 2017 demonstrates proper use of asynchronous promise values using callbacks.
[Zayo private repository](https://github.com/krystin987/maprefactor)

---

- [ ] Understanding of asynchronous concepts and implications such as callbacks


- [ ] Ability to implement AJAX calls in a project


- [ ] Understanding the difference between HTTP methods (get, post, load, etc) and their uses


- [ ] Understanding of error handling and promises

##### HTTP Methods

#####

- [ ] Understands difference between HTTP Methods POST, GET, and PUT


- [ ] Understands difference between AJAX and HTTP Methods -


##### jQuery

- [ ] Understands where to inject script files and how to make it function


- [ ] Understanding of basic operations & functions


- [ ] Able to add localized scripts

### 3. DATABASE DEVELOPMENT



- [ ] Understands the difference between a relational database and document based database

##### MongoDB

- Knowledge of basic installation of MongoDB and C Driver, JSON, schema design, querying, insertion of data, indexing & working with C# driver
- Able to build a MongoDB-based app
- Can Write repository methods that perform basic CRUD operations
- Able to interact with MongoDB documents, & database collections using either RoboMongo or MongoVUE

**SQL**

- [ ] Can create tables, columns & stored procedures in a timely manner

- [ ] Can take business logic and turn it into a database design


- [ ] Knowledge of how to make a primary key or foreign key & how all the relationships work


- [ ] Can create reliable, tested queries that efficiently return data


- [ ] Comfortable with CLI and/or GUI tools


- [ ] Can write repository methods that perform basic CRUD operations
      - *Demonstrated in MVCMovie project: https://github.com/econno11ee/MvcMovieApp*

### 4. BACKEND DEVELOPMENT

##### C# ####

- [ ] Solid understanding of object-oriented programming in C#


- [ ] Knowledge of Visual Studio, can identify Solution Explorer, the debugging menu, the build, run, and clean functions & unit testing


- [ ] Understanding all common modifiers (static, abstract, etc) & can build and implement classes correctly
      - *Demonstrated in MVCMovie project:* https://github.com/econno11ee/MvcMovieApp


- [ ] Understanding namespaces & how to import dependencies


- [ ] Knowledge on how to use model binding
      - *Demonstrated in MVCMovie project:* https://github.com/econno11ee/MvcMovieApp


- [ ] Knowledge of serialization and deserialization with JSON


- [ ] Understanding the difference between pass by reference and pass by value

##### Ruby on Rails

- Understand how an application accesses stored data, and how to reduce load by streamlining data requests
- Strong knowledge of gems, both to locate and install simple add-ons to their application, and create their own custom gems
- Knowledge of unit testing and Spec to produce clean, tested code

##### PHP

- Solid understanding how to use forms
- Understaning of how to assign variables into HTML elements
- Before writing a function or class, be able to utilize existing functions or classes

##### APIs

- [ ] Create modern, REST API's from existing information assets


- [ ] Integrates and orchestrates enterprise services across silos


- [ ] Secure and authorize information assets exposed via APIs


- [ ] Understanding C.R.U.D

### 5. CODING STANDARDS

##### Code Formatting

- [ ] While going through code, check the code formatting to improve readability and ensure there are no blockers

##### Architecture

- [ ] Separation of Concerns followed


- [ ] Split into respective files (HTML, JavaScript and CSS)


- [ ] Split into multiple layers and tiers as per requirements (Presentation, Business, and Data Layers)


- [ ] Code is in sync with existing code patterns/technologies


- [ ] Design patterns: Use appropriate design pattern (if if helps), after completely understanding the problem and context

##### Coding Best Practices

- [ ] No hard coding, use constants/configuration values


- [ ] Group similar values under an enumeration (enum)


- [ ] Comments - Do not write comments for what you are doing, instead write comments on why you are doing. Specify about any hacks workaround and temporary fixes. Additionally mention pending tasks in your to-do comments, which can be tracked easily


- [ ] Avoid multiple if/else blocks


- [ ] Use framework features, wherever possible instead of writing custom code

##### Non Functional Requirements

- [ ] a.) Maintainability (Supportability) - The application should require the least amount of effort to support in the near future. It should be easy to identify, fix, and detect.

      ​	Readability: Code should be self-explanatory. Get a feel of story reading. while going through code. Use appropriate name for variables, functions and classes. If you are taking more time to understand  the code, then either code needs refactoring or at least comments have to be written to make it clear.

      ​	Testability: The code should be easy to test. Refactor into separate function (if required). Use interfaces while talking to other layers, as interfaces can be mocked easily. Try to avoid static functions, singleton classes as these are not easily testable by mocks.

      ​	Debug-ability: Provide support to log the flow of control, parameter data and exception details to find the root cause easily. if you are using Log4Net like component then add support for database logging also as querying the log table is easy.

      ​	Configurability: Keep the configurable values in place (XML file, database table) so that no code changes are required, if the data is changed frequently.


- [ ] b.) Reusability

      ​	DRY (Do not Repeat Yourself) principle: The same code should not be repeated more than twice

      ​	Consider reusable services, functions and components

      ​	Consider generic functions and classes


- [ ] c.) Reliability - Exception handling and cleanup (dispose) resources.



- [ ] d.) Extensibility - Easy to add enhancements with minimal changes to existing code. One component should be easily replaceable by a better component.



- [ ] e.) Security - Authentication, authorization, input data validation against security threats such as SQL injections and Cross Site Scripting (XSS), encrypting the sensitive data (passwords, credit card information etc.)



- [ ] f.) Performance

      Use a data type that best suits the needs such as StringBuilder, generic collection classes

      Lazy loading asynchronous and parallel processing

      Caching and session/application data

- [ ] g.) Scalability - Consider if it supports a large user base/data? Can this be deployed into web farms?



- [ ] h.) Usability - Put yourself in the shoes of a end-user and ascertain, if the user interface/API is easy to understand and use. If you are not convinced with the user interface design, then start discussing your ideas with the business analyst


##### Object-Oriented Analysis and Design (OOAD) Principles

- [ ] Single Responsibility Principle (SRS): Do not place more than one responsibility into a single class of function, refactor into separate classes and functions


- [ ] Open Closed Principle: While adding new functionality, existing code should not be modified. New functionality should be written in new classes and functions


- [ ] Liskov substitutability principle: The child class should not change the behavior (meaning) of the parent class. The child class can be used as a substitute for a base class.
      - Completed Interface Polygons class


- [ ] Interface segregation: Do not create lengthy interfaces, instead split them into smaller interfaces based on the functionality. The interface should not contain any dependencies (parameters), which are not require for the expected functionality
      - Demonstrated in MVCMovie project: https://github.com/econno11ee/MvcMovieApp


- [ ] Dependency Injection: Do not hardcode the dependencies, instead inject them

### 6. GIT

- [ ] Solid knowledge of how source control works why it's important using either CLI or GUI tools


- [ ] Know the basic commands: clone, push, fetch, pull, commit


- [ ] Understand what remotes are


- [ ] Understand how to hide, add, remove, and stash files


- [ ] Understand how to branch and merge


- [ ] Understand how to resolve merge conflicts


- [ ] Can reliably commit based on project needs, with communication to the rest of the team


- [ ] Uses relevant and important information in commit notes


- [ ] Understands differences between HTTPS SSH validation
