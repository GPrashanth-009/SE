UNIT- I    Introduction to Software Engineering
Nature of Software
1. What is software?
Software is a set of instructions and associated data that tells the computer what to do.
2. How is software different from hardware?
Hardware is the physical device; software is the program that runs on it.
3. Characteristics of good software?
Reliable, efficient, maintainable, usable, and secure.
4. Why is software engineered and not manufactured?
Software is developed, not physically produced; it involves design and logical construction, not fabrication.
5. Why is software difficult to maintain?
Because requirements change, technology evolves, and old code becomes complex over time.
________________________________________
Software Application Domains
6. Name different application domains.
Business, embedded, scientific, web apps, AI apps, system software.
7. Example of embedded systems?
Airbag systems, washing machines, medical devices.
8. Difference between system and application software?
System software manages hardware; application software performs user tasks.
9. What is web-based software?
Software that runs on browsers over the internet.
10. Example of enterprise software?
ERP systems like SAP, HR management systems.
________________________________________
Legacy Software
11. What is legacy software?
Old software still in use despite being outdated.
12. Why still used?
Because it is stable, business-critical, and expensive to replace.
13. Challenges in maintaining legacy software?
Poor documentation, old technologies, lack of skilled developers.
14. What is software re-engineering?
Improving or restructuring existing software without changing functionality.
15. When should legacy software be replaced?
When it becomes too costly or risky to maintain.
________________________________________
Software Myths
16. What is a software myth?
A false belief about software development.
17. Example of management myth?
"Adding more people to a late project will make it faster."
18. Example of customer myth?
"Software requirements can be changed anytime with no impact."
19. Why are myths harmful?
They create wrong expectations and mislead teams.
20. Difference between myth and reality?
Myths are assumptions; reality is based on engineering principles.
________________________________________
Software Process Structure
Layered Technology
21. What are the four layers?
Quality focus, process, methods, and tools.
22. Why is process the core?
It defines the framework for methods and tools.
23. Role of methods?
They provide technical steps to build software.
24. What are tools?
Software that supports methods, like IDEs, testing tools.
25. How do tools support development?
They automate and simplify tasks.
________________________________________
Process Framework
26. What is a process framework?
A structure containing essential activities to develop software.
27. Name umbrella activities.
Project management, risk management, configuration management, quality assurance.
28. What is communication activity?
Understanding customer requirements.
29. What is deployment activity?
Delivering and installing the software to the user.
30. Why is tracking important?
To ensure the project stays on schedule and budget.
________________________________________
Generic Process Model
31. What is a generic process model?
A general set of development activities applicable to any project.
32. Main activities?
Communication, planning, modeling, construction, deployment.
33. What is inception?
Initial phase to understand the project vision.
34. What is construction?
Coding and testing parts of the system.
35. What is maintenance?
Updating and fixing software after release.
________________________________________
Process Models
Waterfall Model
36. What is the waterfall model?
A linear step-by-step software development model.
37. Why called linear sequential?
Each phase must be completed before the next begins.
38. Major drawback?
No feedback between phases; not suitable for changing requirements.
39. When suitable?
For stable and well-understood requirements.
40. Explain any phase.
Example: Design phase – turning requirements into architecture and design models.
________________________________________
Incremental Process Models
41. What is the incremental model?
Software is built and delivered in small parts called increments.
42. Difference from waterfall?
Allows partial delivery; more flexible.
43. What is an increment?
A functional part of the system delivered to the customer.
44. Advantage?
Early delivery and customer feedback.
45. Suitable example?
Online shopping application (features can be added in increments).
________________________________________
Evolutionary Process Models
46. What is evolutionary model?
Software evolves through repeated cycles (iterations).
47. What is prototyping model?
Building a quick working model to understand requirements.
48. What is spiral model?
A risk-driven model combining prototyping and waterfall.
49. Strength?
Handles unclear or changing requirements.
50. Why risk analysis important?
Because decisions in each cycle depend on evaluating risks.
________________________________________
Agile and DevOps
Agile Process
51. What is Agile?
A flexible, iterative development approach.
52. What is the Agile Manifesto?
A set of values that focus on individuals, working software, customer collaboration, and adaptability.
53. Two Agile principles?
Early delivery and responding to change.
54. What is iterative development?
Building software in repeated small cycles.
55. Why preferred?
Fast delivery, flexibility, continuous feedback.
________________________________________
Scrum Methodology
56. What is Scrum?
A popular Agile framework for managing projects.
57. Key roles?
Product Owner, Scrum Master, Development Team.
58. What is a sprint?
A time-boxed development cycle (usually 2–4 weeks).
59. Daily Scrum?
A 15-minute daily meeting to track progress.
60. What is a product backlog?
Prioritized list of features and requirements.
________________________________________
DevOps
61. What is DevOps?
A culture that integrates development and operations for faster delivery.
62. Difference from Agile?
Agile focuses on development; DevOps covers development + deployment.
63. Benefits of DevOps?
Faster delivery, automation, better collaboration, fewer failures.
64. What is CI/CD?
Continuous Integration and Continuous Delivery/Deployment.
65. What is continuous integration?
Frequently merging code and testing it automatically.
________________________________________
DevOps Lifecycle & Delivery Pipeline
66. Stages of DevOps lifecycle?
Plan → Code → Build → Test → Release → Deploy → Monitor.
67. What is continuous testing?
Automated testing at every stage.
68. What is continuous deployment?
Automatically deploying software to production.
69. What is continuous monitoring?
Tracking application performance in real time.
70. What is a DevOps pipeline?
Automated steps that move code from development to production.


UNIT – II – VIVA QUESTIONS WITH DETAILED ANSWERS
________________________________________
⭐ A. UNDERSTANDING REQUIREMENTS
________________________________________
1. What are functional requirements? Give 3 real-time examples.
Answer:
Functional requirements describe what the system should do. They define the system’s behaviors, functions, and operations.
Examples:
1.	An ATM must allow users to withdraw money.
2.	A food delivery app should allow placing orders.
3.	An email system must send and receive messages.
________________________________________
2. What are non-functional requirements? List different types of NFRs.
Answer:
Non-functional requirements define how well the system performs the functions.
They describe quality attributes like speed, security, reliability.
Types: Performance, Usability, Scalability, Reliability, Availability, Maintainability, Security.
________________________________________
3. Difference between FR and NFR with examples.
Functional Requirements	Non-functional Requirements
What system should do	How system should work
Example: User login	Example: Login must occur in <2 seconds
Feature-based	Quality-based
________________________________________
4. Why are non-functional requirements important?
Answer:
Because even if features work, the system fails if:
– It is slow
– Not secure
– Cannot handle users
– Is difficult to use
NFRs ensure quality, reliability, performance.
________________________________________
5. Five functional & five non-functional requirements of a food delivery app.
Functional:
1.	User can register/login.
2.	User can add items to cart.
3.	User can make payment.
4.	Delivery boy can update order status.
5.	Admin can manage restaurants.
Non-Functional:
1.	App should load within 3 seconds.
2.	Support 50,000 simultaneous users.
3.	Use encrypted communication (HTTPS).
4.	99.9% system availability.
5.	Easy-to-use UI.
________________________________________
6. What is usability requirement? Example.
Answer:
Usability requirement ensures ease of use of the system.
Example: New users should learn to use the app within 5 minutes.
________________________________________
7. What is performance requirement? Example.
Answer:
It defines response time, speed, throughput.
Example: Search results must load in <1 second.
________________________________________
8. Define security requirement and why critical.
Answer:
Security requirement ensures data protection, authentication, authorization.
It is critical because it protects:
– User data
– Financial information
– Prevents hacking and attacks
________________________________________
9. What happens if NFRs are not documented?
Answer:
•	System may become slow
•	Poor user experience
•	High failure rate
•	Rework cost increases
•	System may crash under load
________________________________________
10. Can scalability be a functional requirement? Why?
Answer:
No.
Scalability is a quality attribute, not a function.
It explains how well the system handles more users, not what it does.
________________________________________
________________________________________
⭐ 2. USER REQUIREMENTS
________________________________________
11. What are user requirements?
High-level, simple descriptions of what users expect from a system.
________________________________________
12. Why avoid technical words in user requirements?
Users may not understand technical language; it creates confusion.
________________________________________
13. What is the purpose of user stories?
To express requirements from the user's perspective.
________________________________________
14. Explain "As a user, I want…" format.
It is used in Agile:
As a <user>, I want <goal> so that <benefit>.
________________________________________
15. Two user requirements for ATM.
1.	User should be able to check account balance easily.
2.	User should be able to withdraw cash quickly.
________________________________________
________________________________________
⭐ 3. SYSTEM REQUIREMENTS
________________________________________
16. What are system requirements?
Detailed, technical requirements used by developers.
________________________________________
17. Difference between user and system requirements.
User Requirements	System Requirements
High-level	Technical detailed
For customers	For developers
Natural language	Structured format
________________________________________
18. Two system requirements for E-ticketing system.
1.	System must store booking data in MySQL database.
2.	System shall generate a PDF ticket after payment.
________________________________________
19. Importance of system requirements.
They act as a blueprint for design, coding, testing, and maintenance.
________________________________________
20. What is functional decomposition?
Breaking complex functions into smaller, manageable sub-functions.
________________________________________
________________________________________
⭐ 4. SOFTWARE REQUIREMENTS SPECIFICATION (SRS)
________________________________________
21. What is SRS?
A document containing complete description of system requirements.
________________________________________
22. Why is SRS a contract?
Because both customer and developer agree on the requirements before development.
________________________________________
23. Characteristics of a good SRS:
•	Complete
•	Consistent
•	Unambiguous
•	Modifiable
•	Verifiable
•	Traceable
________________________________________
24. Explain IEEE 830 SRS structure.
Includes:
1.	Introduction
2.	Overall description
3.	System features
4.	External interfaces
5.	Nonfunctional requirements
6.	Appendices
________________________________________
25. What is requirement traceability?
Tracking requirements throughout development (design → code → test).
________________________________________
26. Purpose of constraints in SRS.
To specify limitations like:
•	Technology constraints
•	Legal constraints
•	Budget constraints
________________________________________
27. What if SRS contains ambiguity?
Developers misunderstand, causing wrong features, delays, and rework.
________________________________________
28. What is verifiable requirement?
A requirement that can be tested or measured.
Example: “The system should load in 2 seconds.”
________________________________________
________________________________________
⭐ B. REQUIREMENTS ENGINEERING PROCESS
________________________________________
5. FEASIBILITY STUDIES
________________________________________
29. What is feasibility study?
Analysis to check whether the project is practical, cost-effective, and achievable.
________________________________________
30. What is technical feasibility?
Checks whether required technology, skills, and tools are available.
________________________________________
31. What is economic feasibility?
Checks whether the project is financially beneficial.
________________________________________
32. What is schedule feasibility?
Checks whether project can be completed within the deadline.
________________________________________
33. Why important before requirement gathering?
Avoids wasting time on unachievable projects.
________________________________________
34. What is cost–benefit analysis?
Compares project costs vs expected benefits.
________________________________________
________________________________________
6. REQUIREMENTS ELICITATION
________________________________________
35. What is requirement elicitation?
Process of collecting requirements from stakeholders.
________________________________________
36. Why difficult phase?
Because stakeholders may:
•	Not know what they want
•	Give conflicting requirements
•	Use vague language
________________________________________
37. Elicitation techniques:
•	Interviews
•	Questionnaires
•	Prototyping
•	Brainstorming
•	Observation
•	Workshops/JAD
________________________________________
38. Explain interview technique.
Analyst asks questions (structured or unstructured) to understand requirements.
________________________________________
39. What is prototyping?
Building a temporary model of the system to clarify requirements.
________________________________________
40. Closed vs open-ended questions.
Closed → Yes/No answers
Open-ended → Detailed explanations
________________________________________
41. Who are stakeholders?
People affected by the system.
Example: Users, managers, developers, customers.
________________________________________
42. Problems if requirements not elicited properly.
•	Wrong product
•	Rework
•	Time and cost overruns
•	Low customer satisfaction
________________________________________
________________________________________
7. REQUIREMENTS ANALYSIS
________________________________________
43. What is requirement analysis?
Understanding, refining, and organizing requirements.
________________________________________
44. How to resolve conflicting requirements?
•	Conduct meetings
•	Prioritize requirements
•	Negotiate between stakeholders
________________________________________
45. What is requirement prioritization?
Sorting requirements based on importance.
Example: MoSCoW (Must, Should, Could, Won’t)
________________________________________
46. What is requirement classification?
Grouping requirements into:
•	Functional
•	Non-functional
•	Domain
•	Interface
________________________________________
47. Example of inconsistent requirements.
One requirement says:
“Payment should be cash-only.”
Another says:
“Allow credit card payments.”
________________________________________
48. Why is requirement modeling important?
Helps visualize system using:
•	Use case diagrams
•	Data flow diagrams
•	Class diagrams
________________________________________
________________________________________
8. REQUIREMENTS MONITORING & VALIDATION
________________________________________
49. What is requirement monitoring?
Tracking requirement changes during project lifecycle.
________________________________________
50. Why agile processes monitor requirements continuously?
Because requirements change frequently; Agile adapts quickly.
________________________________________
51. What is requirement validation?
Checking whether requirements are correct, consistent, and complete.
________________________________________
52. What is requirement review?
Formal meeting to detect errors in requirements.
________________________________________
53. Validation using prototyping?
User checks prototype to confirm requirements.
________________________________________
54. Verification vs Validation.
Verification	Validation
Are we building the product right?	Are we building the right product?
Internal	External
Reviews, inspections	User testing
________________________________________
55. What makes a requirement complete and consistent?
•	Covers all cases
•	No contradictions
•	Clear and testable
________________________________________
56. Purpose of generating test cases during validation?
To verify each requirement is measurable and implementable.
________________________________________
________________________________________
⭐ C. GIT & GITHUB
________________________________________
9. VERSION CONTROL
________________________________________
57. What is Version Control System (VCS)?
Software that tracks changes in code, supporting collaboration.
________________________________________
58. Centralized vs Distributed VCS.
Centralized: single server
Distributed: each user has full repo (Git)
________________________________________
59. Why Git is distributed?
Because every developer has a complete copy of the repository.
________________________________________
60. What is a repository?
Folder containing project files + version history.
________________________________________
61. What is commit?
Snapshot of changes.
________________________________________
62. What information does a commit contain?
•	Author
•	Timestamp
•	Commit message
•	File changes
•	Unique commit ID
________________________________________
63. What is staging area?
Place where changes are prepared before commit.
________________________________________
64. git add vs git commit
git add	git commit
Moves files to staging	Saves staged changes
________________________________________
________________________________________
10. BRANCHES
________________________________________
65. What is a branch?
A parallel line of development.
________________________________________
66. Why important?
Allows independent development without affecting main code.
________________________________________
67. Commands:
Create: git branch new
Switch: git checkout new or git switch new
Delete: git branch -d new
________________________________________
68. What is HEAD?
Pointer to the current branch/commit.
________________________________________
69. Feature branching?
Creating branches for individual features.
________________________________________
________________________________________
11. MERGE
________________________________________
70. What is merging?
Combining branches.
________________________________________
71. Fast-forward merge?
When no new commits exist in main branch; pointer simply moves forward.
________________________________________
72. Three-way merge?
Used when both branches have new commits; Git combines them.
________________________________________
73. What is merge conflict?
When Git cannot combine changes automatically.
________________________________________
74. How to resolve conflict?
Edit file → remove conflict markers → commit.
________________________________________
75. Merge vs Rebase.
Merge	Rebase
Keeps history	Rewrites history
Creates merge commit	Linear history
________________________________________
________________________________________
12. REVERT / RESET / RESTORE
________________________________________
76. What is git revert?
Creates new commit that undoes previous commit.
________________________________________
77. What is git reset?
Moves HEAD to earlier commit.
________________________________________
78. Soft vs Mixed vs Hard reset.
Soft → keeps changes staged
Mixed → keeps changes unstaged
Hard → deletes changes completely
________________________________________
79. When revert preferred?
When you want to undo safely without deleting history.
________________________________________
80. What is git restore?
Restores file to previous state.
________________________________________
81. Undo last commit without losing changes?
git reset --soft HEAD~1
________________________________________
________________________________________
13. FORK
________________________________________
82. What is forking?
Creating personal copy of a repo on GitHub.
________________________________________
83. Fork vs clone.
Fork → copy on GitHub
Clone → copy on local machine
________________________________________
84. Why needed in open-source?
Because you cannot edit original project directly.
________________________________________
85. What is Pull Request?
Request to merge your changes to main repo.
________________________________________
86. What is code review?
Review of code by other developers before merging.
________________________________________
________________________________________
14. WORKING WITH REMOTE REPO
________________________________________
87. What is a remote repo?
Repository stored online (GitHub).
________________________________________
88. git fetch vs git pull.
Fetch → download only
Pull → download + merge
________________________________________
89. What is origin?
Default name for remote repo.
________________________________________
90. Push commits to GitHub?
git push origin main
________________________________________
91. What is SSH authentication?
Secure login using SSH keys instead of passwords.
________________________________________
92. Remove a remote repo?
git remote remove origin
________________________________________
93. What is upstream repository?
Original repo from which you forked.



0UNIT – III – VIVA QUESTIONS WITH DETAILED ANSWERS
________________________________________
⭐ A. DESIGN ENGINEERING
1. What is the design process in software engineering?
The design process is a structured approach used to transform the SRS (Software Requirements Specification) into a blueprint for constructing the system.
It includes:
•	Architecture design
•	Component design
•	Interface design
•	Data design
The output is a complete design model.
________________________________________
2. What is design quality?
Design quality represents how well the design meets requirements and how easy it is to implement, maintain, test, and extend.
High-quality design has:
•	Low coupling
•	High cohesion
•	Good modularity
•	Clear interfaces
•	Good performance and reliability
________________________________________
3. What are design concepts?
Major design concepts include:
•	Abstraction – focusing on essential details
•	Modularity – dividing system into manageable units
•	Cohesion – degree to which module elements belong together
•	Coupling – degree of interdependence between modules
•	Information hiding – hiding internal details
•	Architecture – overall structure
•	Patterns – reusable solutions
•	Refinement – making designs more detailed
________________________________________
4. What is a design model?
A design model describes the system architecture and components using diagrams:
•	Architectural design
•	Data design
•	Component-level design
•	Interface design
•	Deployment design
It serves as a blueprint for developers.
________________________________________
________________________________________
⭐ B. ARCHITECTURAL DESIGN
5. What is software architecture?
Software architecture shows the overall structure of a system, including major components and how they interact.
________________________________________
6. Why is architecture important?
Because it determines:
•	Performance
•	Scalability
•	Maintainability
•	Security
•	Reliability
Architecture is the foundation of the system.
________________________________________
7. What are architectural styles?
Architectural styles are predefined patterns for structuring systems. Examples:
•	Layered architecture
•	Client–Server architecture
•	Pipe-and-filter architecture
•	Model–View–Controller (MVC)
•	Microservices architecture
________________________________________
8. What are architectural patterns?
Architectural patterns are general reusable solutions, such as:
•	MVC
•	Repository pattern
•	Broker pattern
•	Master–slave pattern
Patterns help solve common design issues.
________________________________________
9. What is a context model?
A context model shows how the system interacts with external entities such as users, devices, and other systems.
Usually represented using a context diagram.
Example: ATM system interacting with bank server, user, network.
________________________________________
________________________________________
⭐ C. UML – UNIFIED MODELING LANGUAGE
10. What is UML?
UML is a visual modeling language used to represent object-oriented systems.
________________________________________
11. What is a class diagram?
A class diagram describes:
•	Classes
•	Attributes
•	Methods
•	Relationships (association, aggregation, composition, inheritance)
It is used for static structure modeling.
________________________________________
12. What is a sequence diagram?
A sequence diagram shows object interactions over time, focusing on order of messages.
Used to model workflow or a use-case scenario.
________________________________________
13. What is a use-case diagram?
A use-case diagram shows:
•	Actors (users/external systems)
•	Use cases (functions)
•	Relationships among them
Used in requirement gathering.
________________________________________
14. What is a component diagram?
A component diagram shows physical components:
•	Executables
•	Modules
•	Libraries
Used in deployment and implementation design.
________________________________________
________________________________________
⭐ D. MAVEN & JENKINS (BUILD TOOLS & CI/CD)
15. What is Maven?
Maven is a build automation and project management tool for Java.
It uses POM.xml to define dependencies and build instructions.
________________________________________
16. What is POM.xml?
Project Object Model file that contains:
•	Project details
•	Dependencies
•	Plugins
•	Build configuration
It is the core of Maven.
________________________________________
17. How do you install Maven?
Steps:
1.	Download Maven from Apache website
2.	Extract folder
3.	Set environment variable M2_HOME
4.	Add Maven to system PATH
5.	Verify with mvn -version
________________________________________
18. What is Jenkins?
Jenkins is an open-source automation server used for:
•	Continuous Integration (CI)
•	Continuous Delivery (CD)
________________________________________
19. What is Jenkins architecture?
Includes:
•	Master node – handles UI and job scheduling
•	Slave/Agent nodes – execute builds
•	Plugins extend Jenkins functionality
________________________________________
20. What is a Jenkins Pipeline?
A Jenkins pipeline is an automated script defined in a Jenkinsfile that contains stages such as:
•	Checkout from Git
•	Build with Maven
•	Test
•	Create Docker image
•	Deploy
________________________________________
21. What is a Jenkinsfile?
A text file that defines pipeline stages using Groovy syntax.
Example:
pipeline {
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
________________________________________
22. What is Continuous Integration (CI)?
CI means developers frequently integrate code into a shared repository and run automated builds/tests.
________________________________________
23. What is Continuous Deployment (CD)?
CD automates deployment to production after testing.
UNIT – III – VIVA QUESTIONS WITH ANSWERS
________________________________________
⭐ A. DESIGN ENGINEERING
________________________________________
1. What is the design process in software engineering?
Answer:
The design process transforms SRS (Software Requirements Specification) into a blueprint for constructing the system. It involves:
•	Architecture design
•	Component design
•	Interface design
•	Data design
Output: Complete design model that guides developers.
________________________________________
2. What is design quality?
Answer:
Design quality measures how well a design meets requirements and facilitates:
•	Maintainability
•	Testability
•	Reusability
•	Modularity
•	Performance
High-quality design = high cohesion + low coupling.
________________________________________
3. What are design concepts?
Answer:
Key design concepts:
•	Abstraction: Focus on essential details
•	Modularity: Divide system into components
•	Cohesion: Elements in a module belong together
•	Coupling: Interdependence between modules (should be low)
•	Information hiding: Hide internal details
•	Refinement: Convert abstract design into detailed design
•	Patterns: Reusable solutions
•	Architecture: Overall system structure
________________________________________
4. What is a design model?
Answer:
A design model visually represents system architecture and components. Includes:
•	Architectural design
•	Data design
•	Component design
•	Interface design
•	Deployment design
It serves as a blueprint for developers.
________________________________________
⭐ B. ARCHITECTURAL DESIGN
________________________________________
5. What is software architecture?
Answer:
Software architecture defines the overall structure of a system, its components, relationships, and interactions. It guides development and maintenance.
________________________________________
6. Why is architecture important?
Answer:
•	Determines system performance, scalability, and reliability
•	Ensures maintainability and security
•	Serves as the system’s foundation
________________________________________
7. What are architectural styles?
Answer:
Predefined ways to organize a system:
•	Layered architecture
•	Client-server
•	Pipe-and-filter
•	MVC (Model-View-Controller)
•	Microservices
________________________________________
8. What are architectural patterns?
Answer:
Reusable solutions to common problems:
•	MVC pattern
•	Repository pattern
•	Broker pattern
•	Master-slave pattern
________________________________________
9. What is a context model?
Answer:
Shows system interactions with external entities like users, devices, or other systems. Often represented with a context diagram.
Example: ATM system interacts with user, bank server, and network.
________________________________________
⭐ C. CONCEPTUAL MODEL OF UML
________________________________________
10. What is UML?
Answer:
Unified Modeling Language (UML) is a visual modeling language to describe object-oriented systems.
________________________________________
11. What is a class diagram?
Answer:
Shows classes, attributes, methods, and relationships (association, aggregation, inheritance). Used for static structure modeling.
________________________________________
12. What is a sequence diagram?
Answer:
Shows object interactions over time in a particular scenario. Useful for workflow visualization.
________________________________________
13. What is a use-case diagram?
Answer:
Represents:
•	Actors (users/external systems)
•	Use cases (functions)
•	Relationships among them
Used to capture requirements.
________________________________________
14. What is a component diagram?
Answer:
Represents physical components (executables, libraries, modules).
Used for deployment and implementation design.
________________________________________
⭐ D. MAVEN & JENKINS (BUILD TOOLS & CI/CD)
________________________________________
15. What is Maven?
Answer:
Maven is a Java build automation and project management tool. It uses POM.xml to define project dependencies and build instructions.
________________________________________
16. What is POM.xml?
Answer:
Project Object Model file defining:
•	Project metadata
•	Dependencies
•	Plugins
•	Build configuration
It is the core configuration file for Maven.
________________________________________
17. How do you install Maven?
1.	Download Maven from Apache website
2.	Extract folder
3.	Set M2_HOME environment variable
4.	Add Maven to PATH
5.	Verify with: mvn -version
________________________________________
18. What is Jenkins?
Answer:
Jenkins is an open-source automation server for:
•	Continuous Integration (CI)
•	Continuous Delivery/Deployment (CD)
________________________________________
19. Explain Jenkins architecture.
Answer:
•	Master node: Handles UI, scheduling, and controlling builds
•	Slave/Agent nodes: Execute builds
•	Plugins: Extend functionality for integration, testing, deployment
________________________________________
20. What is a Jenkins pipeline?
Answer:
Automated workflow defined in a Jenkinsfile, consisting of stages like:
•	Checkout from Git
•	Build with Maven
•	Run tests
•	Create Docker image
•	Deploy
________________________________________
21. What is a Jenkinsfile?
Answer:
Text file defining pipeline stages using Groovy syntax.
Example:
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
________________________________________
22. What is Continuous Integration (CI)?
Answer:
CI is the practice of frequently integrating code into a shared repository, running automated builds and tests to detect issues early.
________________________________________
23. What is Continuous Deployment (CD)?
Answer:
CD automates deployment to production after CI testing, ensuring faster delivery.


1. What is software testing?
Answer:
Software testing is the process of evaluating a system to find defects, ensure quality, and verify that it meets requirements.
________________________________________
2. What is a strategic approach to software testing?
Answer:
It involves planning, designing, executing, and monitoring tests to ensure:
•	Maximum defect detection
•	Minimum cost
•	Timely delivery
It considers risk, project size, and resources.
________________________________________
3. Difference between Verification and Validation?
Verification	Validation
Are we building the product right?	Are we building the right product?
Focus on process	Focus on product
Activities: Reviews, inspections	Activities: Testing, simulation
________________________________________
4. What is software test strategy?
Answer:
Test strategy defines overall approach for testing, including:
•	Testing levels (unit, integration, system, acceptance)
•	Test techniques (black-box, white-box)
•	Tools, schedules, and responsibilities
________________________________________
5. Test strategies for conventional software
•	Unit testing: Test individual modules
•	Integration testing: Test combined modules
•	System testing: Test the complete system
•	Acceptance testing: Verify against user requirements
________________________________________
6. What is black-box testing?
Answer:
Testing without knowing internal code. Focus on inputs and expected outputs.
Example: Testing login functionality with valid and invalid credentials.
________________________________________
7. What is white-box testing?
Answer:
Testing with knowledge of internal code structure.
Example: Statement coverage, branch coverage, path coverage.
________________________________________
8. What is validation testing?
Answer:
Validates that the software meets user requirements and is fit for use.
________________________________________
9. What is system testing?
Answer:
Testing the complete integrated system for compliance with requirements.
________________________________________
10. What is the art of debugging?
Answer:
Debugging is finding, analyzing, and fixing defects in code using:
•	Logs
•	Breakpoints
•	Debugging tools
•	Test inputs
________________________________________
⭐ B. CONTINUOUS DEPLOYMENT AND CONTAINERIZATION
________________________________________
11. What is containerization?
Answer:
Packaging an application and its dependencies into a single portable container.
Example: Docker containers.
________________________________________
12. What is a Docker image?
Answer:
Read-only template containing the application and environment needed to run it.
________________________________________
13. How to build and push a Docker image?
# Build image
docker build -t username/mysql-app:1.0 .

# Push to Docker Hub
docker push username/mysql-app:1.0
________________________________________
14. What is Docker Compose?
Answer:
Tool to define and run multi-container Docker applications using a YAML file.
________________________________________
15. Sample docker-compose.yaml
version: '3'
services:
  db:
    image: mysql:5.7
    environment:
      MYSQL_ROOT_PASSWORD: root123
  web:
    image: my-web-app:latest
    ports:
      - "8080:80"
    depends_on:
      - db
________________________________________
16. How to deploy multi-container apps using Docker Compose?
docker-compose up -d
docker-compose ps   # Verify running containers
________________________________________
⭐ C. ORCHESTRATION USING KUBERNETES
________________________________________
17. What is container orchestration?
Answer:
Automating deployment, scaling, and management of containers across multiple hosts.
Example: Kubernetes.
________________________________________
18. Core Kubernetes concepts
•	Pod: Smallest deployable unit containing containers
•	Deployment: Ensures desired number of replicas
•	Service: Exposes pods to network
•	Namespace: Organizes resources
________________________________________
19. How to deploy a Pod in Kubernetes?
apiVersion: v1
kind: Pod
metadata:
  name: mysql-pod
spec:
  containers:
  - name: mysql
    image: mysql:5.7
    env:
    - name: MYSQL_ROOT_PASSWORD
      value: "root123"
kubectl apply -f mysql-pod.yaml
kubectl get pods
________________________________________
20. How to create a Deployment to manage Pods?
apiVersion: apps/v1
kind: Deployment
metadata:
  name: mysql-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: mysql
  template:
    metadata:
      labels:
        app: mysql
    spec:
      containers:
      - name: mysql
        image: mysql:5.7
        env:
        - name: MYSQL_ROOT_PASSWORD
          value: "root123"
kubectl apply -f mysql-deployment.yaml
kubectl get deployments
kubectl get pods
________________________________________
21. How to scale a deployment in Kubernetes?
kubectl scale deployment mysql-deployment --replicas=5
kubectl get pods
________________________________________
⭐ D. CONTINUOUS MONITORING USING NAGIOS
________________________________________
22. What is Nagios?
Answer:
Nagios is a monitoring tool used to check:
•	Servers
•	Network
•	Applications
It alerts admins if services fail.
________________________________________
23. Nagios Components
•	Nagios Core: Monitoring engine
•	Plugins: Check health of services
•	NRPE: Remote monitoring
•	Web UI: Dashboard for status
________________________________________
24. Why use Nagios in DevOps?
•	Provides real-time monitoring
•	Sends alerts for failures
•	Helps in continuous monitoring in CI/CD pipelines


UNIT – V – VIVA QUESTIONS
________________________________________
⭐ A. RISK MANAGEMENT
________________________________________
1. What is risk in software engineering?
Answer:
A risk is a potential problem or threat that may negatively affect a software project, causing delays, cost overruns, or failure to meet requirements.
________________________________________
2. Difference between reactive and proactive risk strategies?
Reactive Risk Strategy	Proactive Risk Strategy
Respond after risk occurs	Identify and prevent risks before they occur
Example: Firefighting issues	Example: Risk analysis & mitigation planning
May increase project cost	Reduces cost and improves quality
________________________________________
3. What are software risks?
Answer:
Software risks are uncertain events that can impact:
•	Project schedule
•	Cost
•	Performance
•	Reliability
Examples:
•	Technology risk
•	Requirements risk
•	People risk
•	Schedule risk
________________________________________
4. How do you identify risks?
Answer:
•	Brainstorming sessions
•	Checklists
•	Historical data
•	Expert judgment
•	Risk workshops
________________________________________
5. What is risk projection?
Answer:
Assessing the impact and likelihood of identified risks to prioritize them for mitigation.
________________________________________
6. What is risk refinement?
Answer:
Continuously reviewing and updating risks, their impact, and mitigation strategies during project lifecycle.
________________________________________
7. What is RMMM?
Answer:
RMMM = Risk Mitigation, Monitoring, and Management
It involves:
•	Planning for mitigation
•	Monitoring risks
•	Managing risks proactively
________________________________________
8. What is an RMMM plan?
Answer:
A documented strategy specifying:
•	Identified risks
•	Mitigation actions
•	Contingency plans
•	Monitoring responsibilities
________________________________________
9. Why is risk management important?
Answer:
•	Reduces chances of project failure
•	Minimizes cost and delays
•	Improves software quality and reliability
•	Increases stakeholder confidence
________________________________________
⭐ B. CLOUD SERVICES AND AWS
________________________________________
10. What is cloud computing?
Answer:
Cloud computing provides on-demand access to computing resources (servers, storage, databases, networking, software) over the internet.
________________________________________
11. What are the main types of cloud services?
Service Model	Description	Example
IaaS	Infrastructure as a Service	AWS EC2, S3
PaaS	Platform as a Service	AWS Elastic Beanstalk
SaaS	Software as a Service	Gmail, Office 365
________________________________________
12. What are the benefits of cloud computing?
•	Cost savings (pay-as-you-go)
•	Scalability and elasticity
•	High availability
•	Easy deployment and maintenance
•	Global accessibility
________________________________________
13. What is AWS?
Answer:
Amazon Web Services (AWS) is a cloud platform offering services like compute, storage, database, networking, and deployment for web applications.
________________________________________
14. How to create cloud infrastructure using AWS?
•	Sign in to AWS Management Console
•	Create EC2 instances (virtual servers)
•	Configure security groups and network
•	Use S3 for storage
•	Launch web applications
________________________________________
15. How to deploy a web application on AWS?
•	Upload application to EC2 instance or Elastic Beanstalk
•	Configure security group, ports (e.g., 80, 443)
•	Start the service and verify via public IP/URL
________________________________________
16. What is the difference between EC2 and S3?
Service	Description
EC2	Virtual server for running applications
S3	Object storage for storing files/data
________________________________________
17. What is the purpose of security groups in AWS?
Answer:
Acts as a virtual firewall controlling inbound and outbound traffic to EC2 instances.
________________________________________
18. What is scalability in cloud computing?
Answer:
Ability to increase or decrease resources dynamically based on demand.
Example: Adding more EC2 instances during traffic spikes.
________________________________________
19. What is elasticity in cloud computing?
Answer:
Automatic scaling up or down to match workload, ensuring efficient resource usage.
________________________________________
20. Difference between public, private, and hybrid cloud?
Type	Description
Public	Shared resources over the internet (AWS, Azure)
Private	Dedicated resources for an organization
Hybrid	Combination of public and private cloud

