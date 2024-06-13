# SE Assignment.

### 1. What is software engineering, and how does it differ from traditional programming? Software Development Life Cycle (SDLC):

__Software engineering__ is a systematic approach to the development, operation, and maintenance of software. It involves applying engineering principles to software development, focusing on the entire software development life cycle, including requirements, design, construction, testing, maintenance, and management.

__Differences:__
- **Scope**: Software engineering encompasses the entire software development process, including planning, design, testing, and maintenance, while traditional programming typically focuses on writing code to solve specific problems.
- **Methodology**: Software engineering emphasizes the use of systematic and disciplined approaches to software development, such as Agile, Waterfall, or DevOps, while traditional programming may involve ad-hoc or informal coding practices.
- **Quality Assurance**: Software engineering places a strong emphasis on quality assurance, including testing, debugging, and maintenance, to ensure the reliability and robustness of the software, whereas traditional programming may have a narrower focus on writing code without as much emphasis on comprehensive testing and maintenance.
- **Team Collaboration**: Software engineering often involves collaboration among multidisciplinary teams, including developers, testers, project managers, and stakeholders, while traditional programming may be more individual-focused.

---

### 2. Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

*SDLC* is the cost-effective and time-efficient process that development teams use to design and build high-quality software with a goal to minimize project risks through forward planning so that software meets customer expectations during production and beyond.

There are 7 Phases of the Software Development Life Cycle:

|  phase | Description |
| ------ | ----------  |
| 1. planning and Analysis| Involves gathering business requirements from your client or stakeholders. This is where the feasibility of creating the product, revenue potential, the cost of production, the needs of the end-users, among others is evaluated.|
| 2. Define Requirements| The information gathered during planning and analysis is converted to clear requirements for the development team.|
| 3. Design | Developers outline the details of the overall application alongside specific aspects such as its: User interfaces, system interfaces, network and network requirements, databases e.t.c.|
| 4. Development | Involves writing the actual code and building the application according the the earlier design documents and outlined specifications.|
| 5. Testing| The application is tested for bugs and ensuring that the end-user would not be influenced negatively by the end product while ensure quality is maintained.|
|6. Deployment| The software is theoretically ready for the market and may be provided to the end users after it has been integrated into its enviroment and installed.|
|7. Maintenance| On deployment, developers begin practicing any activities required to handle issues reported by the end-users.|

## Agile vs. Waterfall Models:

__Agile Model__ is a combination of iterative and incremental models. The focus is given to process adaptability and customer satisfaction.

__Watefall Model__ is a famous and good version of SDLC for software Engineering. It is a linear and sequential model which means that a development phase cannot begin until the previous phase is completed. Phases cannot overlap in the waterfall model

### Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

| <u>Aspect</u> | <u>Agile</u> | <u>Waterfall</u> |
| ------ | ----- | --------- |
| Life Cycle | It is continuous iteration life cycle model to develop and test software product| It is linear sequential model to develop and test a software product.|
| Process | The entire development process is divided into sprints | The Development process is divided into different phases. |
| Flexibility | It is flexible to make changes at any point of time (or at any stage of development) | To make changes after one phase is difficult and costly. |
| Client Involvement | Continuous client interaction and feedback | very little client involvement and very little feedback is taken. |
| Delivery Time | Very short and functional software is available very quickly | very long and the entire project must be completed before delivery. |

## 3. Requirements Engineering.

### What is Requirements Engineering?
__Requirements Engineering__ is the process of identifying, eliciting, analyzing, specifying, validating and managing the needs and expectations of stakeholders for a software system.

### Requirements Engineering Process.
#### 1. Feasibility Study.
Feasibility Study mainly concentrates on the areas below. Among these, the _Economic Feasibility Study_ is the most important part of the feasibility analysis and the legal Feasibility Study is less considered feasibility analysis.
1. **Technical feasibility**: Both the hardware and software along required technology are analyzed/assessed to develop the project.
2. **Operational feasibility**: The degree of providing service to requirements is analyzed along how easy the product will be to operate and maintain after deployment.
3. **Economic feasibility**: Costs and benefit of the project are analyzed.

#### 2. Requirements Elicitation.
This is the process of gathering information about the needs and expectations of stakeholders for a software system. The goal of this step is to understand the problem that the software system is intended to solve and the needs and expectations of the stakeholders who will use the system.

Several techniques can be used to elicit requirements, including:
- Interviews: One-on-one conversations with stakeholders to gather information about their needs.
- Surveys: Distributing questionnaires to stakeholders to gather information about their needs.
- Focus Groups: small groups of stakeholders who are brought to discuss their needs and expectations of the system.
- Observation: This technique involves observing the stakeholders in their working environment to gather information about their needs and expectations.
- Prototyping: Involves creating a working model of the software system, which can be used to gather information from stakeholders and to validate requirements.

#### 3. Requirements Specifications.
This is the process of documenting the requirements identified in the analysis step in a clear, consisnt and unambiguous manner. This also involves prioritizing and grouping the requirements into manageable chunks.

Several types of requirements are commonly specified in this step, including:
- __Functional Requirements__: These describe what the software system should do.
- __Non-Functional Requirements__: These describe how well the software system should do it.
- __Constraints__: These describe any limitations or restrictions that must be considered when developing the software system.
- __Acceptance Criteria__: These describe any limitations or restrictions that must be met for the software system to be considered complete and ready for release.

#### 4. Requirements Verification and Validation
This is the process of checking that the requirements for a software system are complete, consistent and accurate and that they meet the needs and expectations of the stakeholders. The goal is to ensure that the software system being developed meets the requiremsents and that it is developed on time, within budget and to the required quality.

### 5. Requirements Management.
Is the process of analyzing, documenting, tracking, prioritizing and agreeing on the requirement and controlling communication with relevant stakeholders. It is the process of managing the requirements throughout the software development life cycle including tracking and controlling changes and ensuring that the requirements are still valid and relevant.

## 4. Software Design Principles:

### Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

__Modularity__ refers to the practice of dividing software into separate independent modules, each responsible for a distinct feature or functionality. This aproach promotes better maintainability, scalability and reusability of code by isolating functional boundaries making complex systems easier to manage and evolve.

It improves maintanability and scalability in software systems in that:
- Change in one module typically does not affect others, making bugs easier to track and fix without risking other parts of the system
- Modules designed for one project can be used in another, saving development time and reducing errors by reusing proven code
- Modular systems can be scaled more readily by adding new modules or enhancing existing ounes without impacting the rest of the system.
- Different teams can work on different modules simultaneously, decreasing development time.

## 5. Testing in Software Engineering
### Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
#### Levels of Software testing
Software testing levels describe the stages of software development when testing is conducted. Generally, there are four progressive testing levels based on the area they focus on the software development process: unit testing, integration testing, system testing, and user acceptance testing (UAT).
- **Unit Testing**: The smallest testable part of the software system is often referred to as a unit: a new code, a refactoring of legacy code. Unit testing is commonly performed early in the development process by the engineers themselves, not the testing team.
- **integration testing**: The objective of the next testing level is to verify whether the combined units work well together as a group.
- **System Testing**: At this level, a complete software system is tested as a whole. System testing includes user flows, performance and security.
- **User Acceptance Testing**: This is where the product is validated against the end user requirements. It is the last stage of the testing process that ensure customers’ expectations are met, verifying acceptance tests on the stories and the features.

#### Importance of software testing in Software engineering.
The importance stems from multiple key factors:
- **Risk Mitigation**: It helps identify defects and failures early in the development process when they are less expensive to fix thereby reducing project risks related to quality, security, performance, e.t.c.
- **Confidence** – Executing a well–planned software test strategy provides confidence that the software works as intended before its release.
- **Compliance** – Testing can ensure that software adheres to standards, regulations, and compliance requirements. This is especially critical for safety–critical systems.
- **User Satisfaction** – Rigorous testing from a user perspective can verify usability, functionality, and compatibility. This increases customer/user satisfaction and reduces negative impacts to an organization’s reputation or finances from poor quality products.
- **Optimization** – Testing provides vital feedback that can be used to continuously improve software quality, user experience, security, performance and other product attributes.
- **Cost Savings** – Investing in testing activities reduces downstream costs related to defects found post–release. It is much cheaper to find and fix bugs earlier in the development cycle.

## 6.Version Control Systems
### What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
__Version Control Systems__, also known as `source control systems` are systems used to keep track and monitor th changes made to a software code.

They help teams to track every individual change by each contributor and help in improving concurrent work from conflicting. Every change made to a source code can potentially introduce new bugs on its own and new software can't be trusted until it is tested.

## 7. Software Project Management:

### Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

#### Role of a software project manager.
The tasks of a software project manage are divided into two major categories:
- Project planning.
- project monitoring and control

_Project planning_ is undertaken immediately after the feasibility study phase and before the starting of the requirement analysis and specification phase. Once a project is feasible, Software project managers start project planning. Project planning is completed before any development phase starts.

- Project planning involves estimating several characteristics of a project and then plan the project activities based on these estimations.
- Project planning is done with most care and attention.
- A wrong estimation can result in schedule slippage.
- Schedule delay can cause customer dissatisfaction, which may lead to a project failure.  
- Before starting a software project, it is essential to determine the tasks to be performed and properly manage allocation of tasks among individuals involved is the software development.
- Hence, planning is important as it results in effective software development.
- Project planning is an organized and integrated management process, which focuses on activities required for successful completion of the project.
- It prevents obstacles that arise in the project such as changes in projects or organizations objectives, non-availability of resources, and so on.
- Project planning also helps in better utilization of resources and optimal usage of the allotted time for a project.
- For effective project planning, in addition to a very good knowledge of various estimation techniques, experience is also very important.


## 8. Software Maintenance:

### Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

__Software Maintenance__ is the process of modifying, changing, and updating a software system or module to resolve errors, improve performance, or adapt to a changing environment.

#### Types of Software Maintenance
- **Corrective Maintenance**: This involves fixing errors and bugs in the software system.
- **Patching**: It is an emergency fix implemented mainly due to pressure from management. Patching is done for corrective maintenance but it gives rise to unforeseen future errors due to lack of proper impact analysis.
- **Adaptive Maintenance**: This involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.
- **Perfective Maintenance**: This involves improving functionality, performance, and reliability, and restructuring the software system to improve changeability.
Preventive Maintenance: This involves taking measures to prevent future problems, such as optimization, updating documentation, reviewing and testing the system, and implementing preventive measures such as backups.

#### Importance of software maintenance in software lifecycle.
Software Maintenance must be performed in order to: 

- Correct faults.
- Improve the design.
- Implement enhancements.
- Interface with other systems.
- Accommodate programs so that different hardware, software, system features, and telecommunications facilities can be used.
- Migrate legacy software.
- Retire software.
- Requirement of user changes.
- Run the code fast


## 9. Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?