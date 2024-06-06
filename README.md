[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15215128&assignment_repo_type=AssignmentRepo)

# SE-Assignment-2

Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Submitted by : Shakirudeen Akinyemi

Questions:
Define Software Engineering:

Software engineering refers to the branch of computer science that involves the design, development, testing, and maintenance of software applications. It involves designing applications such as games, payment apps, and social media apps, or designing operating systems that make computers function.

What is software engineering, and how does it differ from traditional programming?

The difference between software engineering and traditional programming is while software engineering focuses on the structure and entire life cycle of the software, the traditional programmers focus strictly on writing code.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:

Plan: At this stage, the development team collects customer requirements using software requirement specification documents. They also state the overall goal of the project and prepare a detailed schedule to achieve it. estimates cost.

Design: The design stage involves analyzing the requirements and determining what tools modules, languages and frameworks are to be used.

Implement: The development team does the actual day-to-day coding.

Test: This stage enables the team to know if the code being developed meets the original desire of the client. They undertake manual and automated testing to identify bugs.

Deploy: This is the process of rolling out the completed code in a production environment where the customer can make use of it. To enable the team to continue to work on bugs while clients use the software, the software is kept in a production environment for the client and the other version is in a Build environment for the software team.

Maintain: This involves fixing bugs, resolving issues, and managing software changes and overall system performance to improve user experience.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

The agile method of designing software involves moving through the development in rapid incremental phases, and iterating throughout the lifecycle while the waterfall method involves a step-by-step approach such that after each phase is completed you move to the next and have little chance of making changes to the previous phase. The agile method enables the team to identify and address issues quickly at a low cost before the problems become significant, unlike the waterfall method where problems arising from an earlier phase will only be detected at a much-advanced stage, which could affect budget, time, and scope. The waterfall model is ideal for small software development projects where requirements are pre-defined and easy to break down, while agile is ideal for bigger projects with huge cost and time implications.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirements Engineering provides a framework for understanding the purpose of a system and the contexts in which it will be used. Or, put another way, requirements engineering bridges the gap between an initial vague recognition that there is some problem to which we can apply computer technology and the task of building a system to address the problem.

Requirements engineering techniques offer ways of dealing with complexity, by systematically breaking down complex problems into simpler ones so that we can understand them better. This involves using a deep understanding of the problem to be solved and ensuring the software and hardware are designed to meet the stated need.

In the software development life cycle, requirement engineering helps the team identify potential conflicts and contradictions in requirements for review before design begins.
For instance, the bank wants to design a ticketing system to manage the huge traffic in the banking hall. Requirements engineering will determine whether the ticketing systems should operate from the customers’ phones, a physical ticketing machine in the banking hall, or both.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularity in software design refers to a design approach whereby a complex software system is broken into separate smaller modules with little interdependencies on one another. This enables different software teams to work on different modules without being overwhelmed by the rest of the complex systems.

Modularity enables software teams to focus on testing and debugging specific code modules quickly. This is because as software systems grow, maintenance becomes challenging, thus, working in modules enables smoother workflow.

For scalability, a modular design enables the team to reuse code and/or additional instances to existing modules only without affecting the entire system.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Unit testing is a software testing type whereby individual components are tested in isolation from the rest of the system to ensure that they work as intended. A unit can be a function or method. For example, a software engineer has written a password script that should have a maximum of 10 characters including special characters. By testing the unit, he will know if the characters don’t exceed 10.

Integration testing is software testing whereby modules or units that have interdependencies are tested together to ensure there’s seamless cooperation between them. For instance, a banking ticketing application will undergo integration testing to ensure user information collected in the front end is stored in the backend as required.

System testing is a testing type whereby the entire software application as a whole is tested to ensure both the front end and back end are functional. This also ensures that the software meets non-functional requirements including security, performance, usability, and compatibility.

Acceptance testing is a functional testing type that is done to verify if the software meets the specified criteria. It is usually done by the users/clients/stakeholders. For example, the bank will test their newly developed app’s login, account management, billing & payments, and statement download to name a few.

Testing is crucial in software development because it enables early detection of issues, improves software quality, better collaboration among team members, and reduces costs arising from security and safety issues, spurs clients’ confidence in the software.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version control systems are source control systems that enable software teams to manage source code over time. It is important in software development because it allows collaboration and helps teams work faster. Teams can track each member’s contribution, and previous changes, and also ensure that concurrent work does not conflict. The code is tracked throughout its lifecycle and coders can revert to previous code versions if a mistake is made.

Types of version control systems include
Git is an open-source distributed system that is used for managing software projects. It is the most commonly used.
Subversion (SVN) is a centralized VCS that keeps the project's files on a single code line making it impossible to branch.
Mercurial is a distributed VCS that allows branching and merging. It enables rapid scaling in collaborative development. As a distributed system, teams can use Mercurial from different locations and computers.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

Planning: A software project manager prepares the blueprint for the entire project. This includes scope, required resources, timeline, budget, execution, communication strategy, and change management.
Leading: A software project manager leads a team of developers, analysts, testers, designers, and technical writers. He is the link between the team and clients.
Execution: The software project manager supervises the implementation of activities throughout all stages of the project. He monitors the team’s reports, writes reports, and initiates feedback and changes.
Time management: Time management is one of the major responsibilities of the software project manager. He manages the team’s daily, weekly, and monthly schedule, and ensures risk management and contingency planning are implemented within acceptable time adjustments.
Budget: The software project manager prepares and manages the budget in line with project objectives. He authorizes and monitors spending without compromising quality.
Maintenance: The software project manager is involved in product testing. This is key to ensuring the final product meets the client’s expectations.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance refers to activities involving the modification of an existing software system to preserve its integrity over its lifetime. As user needs change, and new problems arise, software maintenance helps keep software optimized.

Maintenance activities include
Preparation: personnel, tools, environment, policies, and procedures)
Transition: support during initial operation and warranty period.
Operation: User assistance, monitoring performance, logging defects, and managing release versions.
Modification: Analyze problem reports, conduct impact analysis, designing and implementing changes.
Migration: Retiring old versions with newer optimized modules.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Ethical issues
Algorithm bias
Weak security
Wrong priorities
Corporate ownership of personal data and unethical data collection
Overemphasis on design including addictive design

How to adhere to ethical standards
Be proactive
Be honest
Be accountable
Be responsible
Be a good citizen

Sources
https://www.mtu.edu/cs/undergraduate/software/what/#:~:text=Software%20engineering%20is%20the%20branch,software%20solutions%20for%20end%20users.
https://ca.indeed.com/career-advice/finding-a-job/software-engineering-vs-programming
https://aws.amazon.com/what-is/sdlc/
https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/
https://www.institutedata.com/blog/modularity-in-software-engineering/
https://www.prepbytes.com/blog/system-design/introduction-to-modularity-in-system-design/
https://www.browserstack.com/guide/types-of-testing
https://www.atlassian.com/git/tutorials/what-is-version-control
https://www.wrike.com/project-management-guide/faq/what-is-software-project-management/
https://www.computer.org/resources/software-maintenance
https://fullscale.io/blog/ethical-issues-in-software-development/
https://www.techtarget.com/searchsoftwarequality/tip/5-examples-of-ethical-issues-in-software-development

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
