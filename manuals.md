### Purpose of documentation

This document is developed mainly to standardize the project development process and clarify the work standards and collaboration process of product, design, R&D and testing personnel. Through the implementation of a complete product development management process, to achieve the key links in the corresponding work document output and task records as the precipitation of the project progress, to minimize the interference and impact of human factors on the entire project, efficient and high-quality implementation and implementation of the project to promote.


### Project Development Flow

The overall product development management process is shown below, with some projects omitting non-essential phases (controlled by the product manager) as appropriate:

1.Requirements stage: includes requirements collection, analysis and screening, mainly by product managers for daily product/user requirements collection and relevant version iteration plans.

2.Planning stage: including product solution design and product requirements review, mainly by the product manager output PRD documents, and organize relevant colleagues to conduct requirements review meetings.

3.Design stage: including the finishing and output of the UI design draft, mainly by the UI designer to complete the design draft, and organize the review meeting of the UI design draft by relevant colleagues.

4.Development stage: including architecture design, code design, code implementation, etc., mainly by front and back-end engineers to complete the product architecture, page and logic related development.

5.Testing stage: including functional testing and performance testing, etc., with the test engineer taking the lead and outputting test cases and test reports, and the product and UI assisting in acceptance.

6.Release Online stage: including grayscale release and full release, mainly the project leader to determine the specific release time and release channel, and responsible for the related material publicity.

![英文版](https://user-images.githubusercontent.com/122437870/221514526-a2d2f53e-275a-47ea-b0aa-2465c2fb50a2.png)


### Project Management Tools

#### 1.Github

Due to the open source nature of the CKB project and code management, Github is used as the main project management software.

（1）Issues Management

![image](https://user-images.githubusercontent.com/122437870/221514992-03031ff2-d14f-493e-95be-424926a3eab3.png)

【Create】 Created by users or project members and maintained by relevant personnel

-Category: Create a new issue under the product item category of the issue or requirement.

-Title: Use one sentence to briefly describe the main content of the issue, avoiding redundancy, ambiguity or overly specialized terms.

-Content: Describe the problem and requirements in detail, with relevant screenshots, links, code, etc. if necessary, paying attention to clear paragraphs, clear content and complete narrative.

【Collaboration】Team members complete task splitting and follow-up through notification/comment/assignment functions

-Notification: Pay attention to Github intranet notifications, understand the dynamics of issues, and follow up with their own related issues.

-Comments: Comments & replies should be clear and concise in a timely manner, and quote reply or @ can be used to assist with instructions when necessary.

-Assignment: After the problem or requirement is clear, assign to the corresponding person in the current phase to follow up, and after the completion of this phase, assign to the person in charge of the next phase.

Note: All new requirements are assigned to the product manager, who is responsible for assigning the person in charge of the follow-up.

【Tagging】According to the content marked with different tags for categorization for easy management and tracking

-Feature:New features or requirements added and planned for implementation.

-Enhencement: Optimization of pre-existing features.

-Documentation: Document preparation and archiving requirements.

-QA: Question communication and response.

-Bug: A product defect that clearly exists and needs to be fixed.

-Wontfix:Invalid issues or issues that won't be fixed.

【Projects】Projects are managed by status, priority, scheduling, and Iteration

-Status:New、Hold On、Backlog、Planning、Designing、In Progress、Testing、Pre Release、Done.

-Priority:Urgent、High、Medium、Low.

-Date:Start Processing Date、Expected Done Date、Actual Done Date.

-Iteation

【Close】After the task of each person in charge has been clarified and ended, the product, test or initiator will close

(2) Project Management

Project progress and requirements are managed through the Github project management module, which is maintained by the product manager.

【List】Project requirements pool list, sorted by status, sorted by priority from highest to lowest

【Board】Project task board, classified by status, used to view the current task status

【Schedule】Project schedule, only show the current Iteration's project schedule

#### 2.Google Meet

【Project Weekly Meeting】

Generally held at 10:00 a.m. every Monday, single project time usually ends in 30 minutes or less. The main content of the meeting is project progress management and task planning, including：

-Task progress and difficulties.

-This week's mission plan.

During the meeting, the project leader can make relevant adjustments to the tasks of project members, taking into account the progress and task priorities.

【Other communication meetings】

The following meeting principles should be followed in arranging meeting communication according to the actual situation:

-Plan meetings well in advance to avoid unstructured and non-essential meetings that take up too much time.

-Clarify the purpose of the meeting, moderator control the pace of the meeting, controversial issues do not exceed 5 minutes.

-Speak in an orderly manner, avoid divergent thinking and personal attacks, and discuss issues efficiently.


### Specific implementation process specification

#### 1.Requirements stage

(1) Introduction to Requirements Management

The requirements management phase is the initial stage of product iteration, and product iteration starts from requirements. Specifically, requirements management consists of the following phases:

1.Requirements collection: can be through market research, competitor analysis, user feedback, data analysis, boss/colleague feedback, etc.; collect product user requirements or technical-type requirements

2.Requirement analysis: analyze by scenario analysis method, kano model, etc., and fully communicate the requirement priority and task volume with relevant personnel.

3.Requirements Screening: Screen out the analyzed requirements and develop a new iteration plan for a new version of the product or a long-term version iteration plan.

(2) Participants and their duties

The participants in the requirements management stage are mainly the product managers, but of course any member of the project can propose their own product requirements (including code optimization requirements proposed by the technical engineers, etc.), with the following specific responsibilities.

-Project members: Any project member can come up with his or her own product requirements.

-Product Manager: responsible for requirements collection, analysis and screening, responsible for managing and maintaining the product requirements pool, and developing version iteration plans.

(3) Requirements pool management

Product requirements pool management uses the issues module in the Github project, each project member can create a product requirements feedback to the product, note that when creating requirements do not group the requirements into a particular iteration.

When viewing the requirements pool, simply switch the view to 【Backlog of requirements to be planned】 to view the status of all requirements.

(4) Document output

Iteration planning documents: If a product manager has a long-term project plan during the requirements management phase, he/she needs to plan and split out the monthly and quarterly targets, and needs to upload the finalized documents and share them with the project team members.

Market research documents: the documents produced by the product manager's market research, user interviews, competitor analysis, etc. Again, these documents need to be uploaded and shared with project members.

#### 2.Planning stage

(1) Introduction to product planning

The product planning stage is mainly done by the product manager to transform the requirements into the output of the product solution, including the basic functional flow design, prototyping, PRD document writing, etc.

(2) Participants and their responsibilities

The product planning stage is mainly participated by the product manager, who is responsible for the output of the overall product solution design, including requirements background, requirements objectives, and specific product solutions; after completing the writing of the PRD document, it is necessary to organize and invite relevant personnel for a product requirements review meeting, in which the product solution is clearly stated.

(3)Product Planning Review Meeting

A meeting organized by the product manager, the purpose of the requirements review is to allow the project participants (here mainly refers to the design, development and testing) to quickly understand the intent of the product and approve the adopted solution.

Of course, requirements review is not about who has to convince whom, but we have to find the optimal solution for a specific problem.

Regarding the advancement steps of the planning review：

1.First, the product manager will explain the background and objectives of the requirements and communicate them to the team members.

2.Next, the product manager continues to describe the specific product solution and discusses the feasibility of the solution with team members after each page or feature.

3.Finally, the product manager compiles the meeting minutes and notifies them in the workgroup chat, synchronizing everyone with the results of the meeting.

(4) Document output

-PRD document: mainly written by the product manager, including product background and objective description, global description, detailed product solution description and other modules, after finishing, it needs to be uploaded to Axure Share and the link appendix GitHub corresponding issue for retention.

-Review meeting minutes: After the review meeting, the meeting minutes and results need to be organized and posted to the work group chat, so that everyone can understand the final results of the review meeting and follow up on the controversial parts to improve.

-Project creation email: After the requirements review is agreed, the product manager needs to organize the project content and scheduling project creation email to inform the project content and arrangement, so as to facilitate subsequent filing.

【Email Template】

Title of mail: 【Project】 XXX

Attn: Project Participating Members

Copy to: Project Affiliates and Project Leaders

Content：Background and Purpose/Members and Responsibilities/Content/Scheduling.

#### 3.Design stage

(1) Introduction to UI design

UI design stage is mainly done by UI designers, including doing the visual design of the interface, carrying out the layout, color matching, style different styles of attempts, etc.

(2) Participants and their responsibilities

UI design phase mainly involves UI designers, product managers:

-UI designer: complete the design of UI design drafts, conduct the evaluation of UI design drafts for presentation, etc.

-Product Manager: control the UI design accordingly.

(3) UI design draft review meeting

The review of the UI design draft can be organized by the UI designer, or the product manager can assist the designer in organizing and inviting the project participants to conduct relevant reviews, which are mainly as follows:

【Overall】:

-Whether the design concept is in line with the positioning of the product and whether the overall style is in line with the temperament of the product.

-Whether the color palette is comfortable and the overall tone is consistent and regulated.

-Whether the layout style is balanced and whether there is a lopsided design or a lack of overall coordination.

-Is the content hierarchy clear and unambiguous.

【Details】：

-Whether the design elements are chosen to match the overall style, including size, color, texture, etc.

-Whether elements such as icons and buttons are unified and harmonized with the overall interface.

-Whether there are redundancies or errors, omissions, etc. in text, elements, and other details.

(4) Document output

UI design draft: The UI design draft created by the design software, uploaded to Figma after markup, and appended the relevant links to the corresponding issue on Github for retention.

#### 4.Development stage

(1) Introduction to development

The development phase mainly refers to the code development work done by various types of engineers to implement the product features, pages, and logic.

(2) Participants and their responsibilities

-Front-end engineer: build the front-end framework, realize the static page of the product front-end according to the prototype design draft/UI design draft, and bind the data interface on the basis of the static page.

-Back-end engineer: build the back-end framework, provide all kinds of interfaces required for the product functions in conjunction with the requirement documents, and carry out interface debugging work with the front-end.

-Algorithm Engineer: Build algorithm framework and provide algorithm development work for products.

(3) Code base management

1.Code base permission assignment

-Using the organization's built-in GitLab to save and manage code resources belonging to the organization;

-The Chief Technical Officer and the direct project leader have the Master authority of the project:

  Responsible for the project's authority management
 
  People management within the project
 
  Operation of protected branches

-Technical staff involved in project development are set to Developer privileges;

-White box testers and related personnel are set to Guest privileges.

2.Codebase branch management methods

Branches:

-Create a release (or another name for the same function) branch for the project, dedicated to the release of the production environment;

-Create a develop (or another name for the same function) branch dedicated to test environment releases;

-The Master branch is used to backup the last stable release of code from the release branch. For disaster recovery;

-Set the release and master branches to a protected state. Only managers with master privileges can merge and commit code from both branches, and review and trace the code during the merge commit process.

Use:

-Developers need to create a development branch for each task for this task (for personal use only);

-Each developer (different development branches) can merge the code into the develop branch at any time and release it to the test environment by someone with access to it. If anything happens to the develop branch, the branch with the same name can be deleted and rebuilt at any time, and this branch does not have to worry about contamination;

-After all the code in the development branch has been developed and tested in the develop branch. Each developer needs to initiate a merge request to the release branch, and the project leader will code review and complete the merge (leave a trace). If there is any conflict, specific developers need to cooperate with the project leader to resolve the conflict;

-After the code is merged into the release branch, it needs to be regression tested. The project leader will release the code to the production environment after it is error free.

![英文](https://user-images.githubusercontent.com/122437870/221747065-364eca8e-014f-4528-aef6-a190e0cee652.png)

#### 5.Testing stage

(1) Test Introduction

The testing stage is mainly done by test engineers, who test the product according to the test cases written by the PRD document to find the bugs and defects in the product interface, functions and those that do not meet the product requirements document.

The development team has to make changes to the defects during this phase, and the test engineers need to track the fixes of the defects.

(2) Participants and responsibilities

The testing stage involves mainly testers and developers:

-Testers: understand the background of the project, get familiar with the requirements of the product, write test cases for the product through the product requirements document, organize and invite relevant personnel for a review meeting of the product test cases, in which the testers explain the principles of writing their own test cases to the other participants. After the meeting, the testers test the product. Before testing, they need to confirm the version number and version name of the current test version with the product manager and follow up the test defects submitted.

-Developers: code fixes for defects found by testers.

-Project members: All project members should try to participate in the testing process and raise the bugs found so that the product can be improved before going online.

(3) Test case review meeting

The test case review meeting is organized by the test engineer with the participation of relevant project personnel, and the meeting process should focus on the following points:

1.The clarity of the description of the test case itself and the presence of duality;

2.Whether the efficiency of test case execution is taken into account, often the steps in the test cases are repeatedly executed with different validation points, and the redundancy of the test design, all of which contribute to inefficiency;

3.Whether all product requirements are covered;

4.Whether the product design requirements have been fully complied with, i.e. matched to the PRD document.

(4) Document output

Test Case: Test Case (Test Case) is a set of test inputs, execution conditions and expected results prepared for a particular goal in order to test whether the product can go online normally.

Test report: Test report is to write the process and results of the test into a document, analyze the problems and defects found, and provide a basis for correcting the quality problems of the product, as well as laying the foundation for product test acceptance and delivery.

The test report contains the test purpose, project background, test arrangement, test plan, test results, defect analysis, test summary and other elements, which should also be uploaded to Github for retention in the corresponding issue after completion of writing.

#### 6.Release Online stage

(1) Release Online Introduction

Product release online is a milestone event for the project team, meaning that the product code is switched from the test environment to the official production environment, and the product can be accessed directly by ordinary external users by updating the app or opening the online web link.

(2) Participants and responsibilities

The main participants in the product launch include project leaders, product managers, developers, etc.

-Project leader: determine the release version, release time and release channel of the project.

-Product manager: do final regression testing before release online, find obvious bugs in time, write good product release notes; after the product release online, write product launch release emails for project-wide notification.

-Development engineers: to carry out the sealing work, while the project leader agreed to submit the release application.

(3) Grayscale release

The so-called grayscale release is to select some users according to a certain strategy and let them experience the new version of the application first. By collecting feedback from these users on the new version of the application and assessing and evaluating the new version's features, performance, stability and other indicators, the decision will be made to continue to scale up the release of the new version until the full upgrade or rollback to the old version.

(4) Document output

Product release notes: the release notes after the product launch, including the product update features, scope, etc., the release needs to be issued after the release email for project-wide notification; APP products through the app store channel for release, but also to write the update notes.

Grayscale test report: Combine with the release of grayscale version, write grayscale test report, including product data summary, user feedback summary, etc., and elaborate the next specific action plan.

------------------------------------------ END 2023.2.28 ------------------------------------------

