[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15235647&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
What is software engineering, and how does it differ from traditional programming?

software engineering is the application of engineering principles, methods and tools to the development and maintainance of high quality software systems.
software engineering differs from the traditional programing in that software engineering involves processes that involve computers, programming and code writing for making application while traditional programming involved building of cars, machines , hardware buildings but not applications.

reference;( https://www.geeksforgeeks.org/difference-between-software-engineering-process-and-conventional-engineering-processs/)

Software Development Life Cycle (SDLC):
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

The software development life cycle  has 6 phases which are;
requirements- involves gathering and documenting user needs and system requirement for the particular software
design- this involves creating high level designs(structure design of the software)and its user interface
implementation- according to the designs chosen, then implementation involve writing a code and building the software depending on the designs
testing- tests are done to ensure the software meets the quality standards and functional requirements
deployment- release to the customers or users
maintainance- providing support, updates and enhancement to promote effeciency.

reference: plp lecture notes on software engineering

Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

agile- this is an interactive and incremental approach focused on flexibility, collaboration and resposive to change. it is mostly used for a long term project as it can bypass some steps making it faster than waterfall.
waterfall-this is an approach with different phases in it, flowing downwards like a waterfall. it is systematic in that each phase must be completed before the next and suitable for short term projects as it takes longer.
agile and waterfall models are different in that waterfall has clear and documentation and rigid while agile is flexible and works with proper stateholder feedback and collaboration

reference from lecture notes

Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.

requirements engineering is the first phase in the SDLC which involves defining, gathering and maintaining the requirements needed to make a software.
the process include; gathering requiremnents for example by reading documents, going for workshops and also having interviews and surveys from the stakeholders. the second step is coming up with a more refined requirement that is agreeable across all the stakeholders as some may have had different opinions thus coming up with a requirement that is suitable for everyone. the next step after that would be documenting the requirements in details so that they can be used as a reference for the designs and development. the next step is checking for the requirements accuracy through having rewiews and inspections and the last step is keeping track of all the requirements, handling changes (updates) and maintaining traceability
importance of requirements engineering is that; it gives understanding of what your target customers want and reduces being ambiguas, it provides the basis for validating and verifying the final product, it prevents high costs and sets the scope for a project while putting in mind the needs of stakeholders thus promotes overall satisfaction with thw finished product. 

reference; (https://softwaremind.com/blog/software-requirements-engineering-the-driving-force-behind-successful-and-efficient-it-projects/)

Software Design Principles:
Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems? 
this is the practice of breaking down a software system into descrete, independent components which encapsulates a specific piece of functionality.
modulating improves maintability  by promoting simplified debugging, making it easier for young  developers to get up to speed as it is easy to read and understand and also the models can be reused
scalability is enhanced  by flexibility deployment which can be done independently thus allowing targetted updates, therse is also performance optimization  is enhanced and also allow different teams to work without each of them disturbing the other(parellel development)
reference: (https://www.secoda.co/glossary/modularity#:~:text=Modularity%20in%20software%20design%20is,them%20down%20into%20digestible%20parts.)

Testing in Software Engineering:
Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

unit testing- this is the testing of individual components or modules of a software. this helps to verify that each individual unit works as expected.
integration testing- this is testing interactions between different components or subsystems. helps to identify issues that may occur when the units are combined such as dataflow systems
system testing- testing the entire system as a whole to ensure it meets the specified requirement.
acceptance testing - testing the software against the user's requirement to ensure it meets the needs of the user.
testing is crucial in software development as it hyelps to identify and fix dects early in the development process, leading to high quality software products and the reduction of the maintenance cost.
reference: from software engineering class notes

Version Control Systems:
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

version control systems are software tools that help in the management  of changes to source code over time allowing developers to collaborate effeciently and track modifications.
examples are Git which is known for its flexibility, merging capabilities and its speed. this is also an open source widely used by other platforms such as github
mercurial is another example that is quite similar yo GIT but it offers a simpler user interface and command set compared to Git.
Subversion is also an example which keeps all of a project's files on a single codeline making it impossible to branch, so it's easy to scale for large projects. 
version systems are crucial  as they enable many developers to work on the same codebase without any interruptions, allows merging and branching and provide a history of changes made and they are done by which specific person.
reference(https://about.gitlab.com/topics/version-control/)

Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

a software project mananger oversees the planning, execution and delivery of software projects.
key responsibility include; project planning, quality assurance in that ensure that the projects meets the standard, facilitating communication amoung the members, identification of potential risks and formulating strategies to solve them(risk manangement), allocating human plus technical resources to meet the requirements of the project(resource management), documenting all project and cost control in that they manage budget and prevent cost overruns.
challanges include; miscommunications, lack of skilled personelle and balancing deadlines, changing requirements and they have to look for strategies to overcome every difficulty that may occur.
reference: lecture notes in class

Software Maintenance:
Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

softwore maintenance is the process of modication and updatation of a software after its release to improve its performance.
corrective maintanance- fixing bugs and errors noticed during the use of a software
adaptive maintenance- modification of a software to accomodate changes that are in the environment example is upgrading the operating system.
perfective maintanace- this improves the performance of a software by adding new features or actually enhancingn the one that exist an example is the features added in Whatsapp
preventive maintenance-this keeps look out for future problems and how to address them to avoid software failure
software maintenance is important  as it promotes longetivity of a software in that it continues being of use and of relevance, promotes the software to adapt to the changes in the environment and the changing user requirements
reference(https://www.computer.org/resources/software-maintenance)

Ethical Considerations in Software Engineering:
What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

ethical issues include: privacy concerns, security vulnerabilities or breaches, environmental impact and the bias in algorithims
software engineers can adhere to ethical standards in their work by being informed and keeping up to date with the ethical guidelines and standards in the industry, conducting ethical assessmentsto evaluate the potential impact to the society, by seeking feedbacks in that they collaborate with colleagues to identify any ethical concerns and by following the coding practices and consider privacy by design principles.
reference (https://www.techtarget.com/searchsoftwarequality/tip/5-examples-of-ethical-issues-in-software-development)
(https://fullscale.io/blog/ethical-issues-in-software-development/#:~:text=Be%20accountable,-You%20should%20strive&text=For%20instance%2C%20you%20should%20avoid,ethical%20issues%20in%20software%20development.)

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
