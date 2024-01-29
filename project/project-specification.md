# SENG 321 Requirements Engineering Project Specification

## Objectives
1. Apply the RE techniques learned in the course in a team project focused on realistic problems.
2.	Gain experience with developing and maintaining a software requirements specification as a living document in a software project.
3.	Gain experience with the activities and expectations of the roles as clients as well as developers in a software project.
4.	Promote student motivation, professionalism, and self-organization by interacting with real stakeholders.
5.	Practice interviewing and stakeholder management skills with real stakeholders and other student groups.
6.	Improve project presentation skills through in-class demos and updates.
7.	Develop strong prototyping skills.

## Context and Management

The requirements documentation in a project is a most powerful tool to document the knowledge, expectations and features of a software system. When managed as a living document, it records the understanding of the needs, the business and user requirements, features and non-functional requirements. It is also a record of decisions made through negotiations between clients and developers of the system. For this project you will be working in a 6-8 student project team in both roles of a **Client** and a **Developer** in **two different projects**. The requirements documentation is developed incrementally and iteratively thoughout the term project and it is the ultimate project deliverable is the course. Clarification: Your team is the same (but play different roles) in the two projects. 

The following diagram covers the main activities for both roles of **Client** and **Developer** across the iterations. 
![Diagram of Project Overview](https://github.com/Uvic-SENG321Spring2024/course/assets/17919332/814b8b5d-3b6e-46c5-9cae-6b5394f2ff65)

The project follows an agile methodology and iteratively develops a number of artifacts such as a **Request for Proposal (RFP)**, **Requirements Documemnt (RD)**, Prototypes and in-class Presentations. **All your project work, must be uploaded to your GitHub repo by the due dates given. See below for instructions on each deliverable, due dates, and instructions on how to use GitHub.**




### Working as a Client
In order to create realistic requirements for a developer team, you, as a client team, must first write an **RFP (Request For Proposal)**. This involves finding a real world organization (RWO) in our community, and gathering a set of requirements based on a problem that they need solved. For example, perhaps a pharmacy in your neighbourhood needs a better system to acquire and manage information about medications to be dispensed. Specific guidelines on how to choose a RWO, and create the **RFP** can be found below in Deliverables.

To ensure you find realistic requirements, your first task is to find a RWO, introduce yourself, and identify a problem in the organization that can benefit from a software solution. You will conduct as many interviews as needed to become familiar with the organization’s system and problem. Subsequently, you will act as representatives of this organization for the duration of this project. Thus, your first deliverable is the **request for proposal (RFP)**. Be sure you know enough about the software solution in order to write the **RFP**. Once you hand in your **RFP**, a **different** team will be assigned to be the corresponding Developer team for the problem that is defined in your **RFP**. As representatives of the problem that can benefit from a software solution, you will act as clients to the designer team for future deliverables. This involves defining in more detail the requirements and constraints for a solution system, as well as other expectations that your organiztion has of the Developer team (i.e. project timing, interaction mode, etc.) The Developer team will then read and understand **your RFP** and throughout the project will interview your organization, "the Cient", on several occations and as needed (see Schedule). During these interviews, you will provide information regarding “your” organization and system. Furthermore, you will provide feedback for the prototypes built by the designer team.


### Working as a Developer
Your team will also act as a consultant contracted to develop a solution to respond to the needs of a client organization (development is not the focus of the project, but performing the requirements engineering activities). The ultimate deliverable is the **Requirements Document (RD)** (including high level external design) for the feature chosen by the clients, which will be delivered in stages through the **RD**. It is the responsibility of the designer team to independently apply the requirements engineering activities in order to produce the deliverables. However, the client team is available and expected to clarify questions regarding the solution. Over the course of the project, the designer team will have several meetings with the client team, which provide you the opportunity to elicit requirements, corroborate understanding, and validate and verify prototypes (use case models, UML, sequence diagrams, data flow diagrams, etc). By the end of the project, your team is expected to turn in a complete **Requirements Document** which will be built in three iterations, and give a final project demonstration to the class.

**NOTE:** your project team will act as a **client** for **one** project and a **designer** for a **different** project.

## GitHub Usage Guidelines
For this project, your team will have write access to two different *repos*. The teaching team will create the two repos on your behalf during the first week of the semester. 
- one *repo* you will use as the *client* team.
- one *repo* you will use as the *developer* team.

### As clients: 
As part of your project work as *clients* you will write up and release your RFP in your client repo. Additionally, you will have read access to the developer team repo who will design the solution for your RFP project. You are expected to create an issue in the developer team repo for any problem/question/concern that you encouter when you review their Requirements Document after each iteration of the project. 

### As developers: 
As part of your project work as *developers* you will write up and iteratively release the Requirements Document in your developer repo. As described above, the Requirements Document that you iteratively work on throughout the semester will be a single, living document that each member of your developer team will be expected to contribute. You are expected to hand in one single markdown file with all the contents of Requirements Document following the format of the [template](https://github.com/Uvic-SENG321Spring2024/course/blob/main/project/Requirements-Document-Template.md). Over the course of the semester, you will continue to add to this document for each iteration as a developer team. 

Since you are expected to work on one markdown file for your Requirements Document, you will need to coordinate within your team who is going to work on each subsection of the markdown file. For instance, one team member may work on the requirements for feature 1, another team member on feature 2, another team member on quality attributes, etc. If you encounter some merge conflicts due to conflicting modifications to the same section, you will need to resolve these merge conflicts as they come up. As part of working on the document, you are expected to merge any of your changes to the main branch of the Requirements Document (whether you are editing or adding to a new section). You will need to submit a pull request for your addition and at least two approvals are submitted before the change may be pushed to the main branch. The approvers will need to watch for the quality criteria for the documentation (i.e., ambiguity, consistency, matching the client documentation in relation to RFP or from elicitation or other meeting notes, lack of conflicts, completeness in relation to client documentation) -- see lecture on documentation.

The client team whose RFP you are responding to will have read access to your developer repo. The client team will review your requirements document after each iteration and create an issue for any problem/question/concern that they see in the Requirements Document. It will be up to your team to address each issue in the form of a pull request. The process for addressing client feedback is the same as above for adding new or editing existing content. You need to submit a pull request with your changes.


## General Project Rules
1. The project comprises about 100-150 hours per person in the student team (depending on how effectively your team collaborates).
2. The total effort must be evenly distributed amongst team members. 

## Deliverables
In this section, the various project deliverables are explained. Material is linked below such that more details can be found in other pages if needed. 

### Request for Proposal (RFP)
#### Guidelines for Choosing Real-World Organizations
As a client team, you will be asked to produce an RFP, which requires you to find an organization with a problem that can be solved with a software solution. Here are some green flags to look for when selecting an organization and problem: 

- The organization demostrates a situation which has a clear need for improvement
- The organization and its problem involve a variety of categories of end-users that are impacted
- The system uses a GUI (Graphical User Interface)
- The organization has availability to be interviewed by your team in the first two weeks of the course.

Here are the [guidelines](https://github.com/Uvic-SENG321Spring2024/course/blob/main/project/Request-for-Proposal/RFP_template.md) for the RFP, which includes the template to use. 

### Requirements Document (RD)
More information will be provided here timely. For now, please see the [template](https://github.com/Uvic-SENG321Spring2024/course/blob/main/project/Requirements-Document-Template.md) for the RD. 

### Prototyping Guidelines
More information will be provided here timely.

### Final Presentation Guidelines
More information will be provided here timely.

### Team Assessments
More information will be provided here timely.
 
## Project Due Dates
**The current due dates are tentative and subject to change** 

| **Deliverable**       | **Description**                                                                  | **Due Date**       | **Role*               |
|-----------------------|----------------------------------------------------------------------------------|--------------------|-----------------------|
| Find Organization     | Find an organization, relevant problem and have interviews scheduled.            | Jan 13- 11pm        | clients               |
| [RFP](https://github.com/Uvic-SENG321Spring2024/course/blob/main/project/Request-for-Proposal/RFP_template.md)                  | Formally propose the relevant problem  with a set of gathered requirements       | Jan 21- 11pm        | clients               |
| [Team Assessment](https://github.com/Uvic-SENG321Spring2024/course/tree/main/project/team-assessment) 1     | Submit survey for team assessment.                                               | Jan 22- 11pm        | reflect on both roles |
| Requirements Document | Include vision and scope section                                                 | Feb 4- 11pm         | designers             |
| Team Assessment 2     | Submit survey for team assessment.                                               | Feb 5- 11pm         | reflect on both roles |
| Requirements Document | Formally propose system diagrams,  user stories, NFRs, acceptance tests          | Feb 17- 11pm        | designers             |
| Team Assessment 3     | Submit survey for team assessment                                                | Feb 26- 11pm        | reflect on both roles |
| Prototypes            | Submit prototypes based on previously  proposed requirements and client feedback | Mar 9- 11pm         | designers             |
| Team Assessment 4     | Submit survey for team assessment                                                | Mar 18- 11pm        | reflect on both roles |
| Final presentation    | Project presentations which include  a demo of final prototypes.                 | Apr 2,3,4 in class  | designers             |
| Team Assessment 5     | Submit survey for team assessment                                                | Apr 8- 11pm         | reflect on both roles |
