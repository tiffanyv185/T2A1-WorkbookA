# T2A1-A: Workbook Part A

## Huyen Tram Tiffany Vo

### Q1.

---

### Q2.

---

### Q3.

Agile project management is a flexbile and repetitive approach to planning and managing a project that emphasises on regular and continuous improvement, collaboration and ability to change (Atlassian, 2019). This is very different to other traditional project management, which often follow a linear process, known as the waterfall project management method. This method requires projects to move through phases sequentially which makes it inflexible as it is difficult to make changes or address unforseen issues once phases are completed (Radigan, D. 2022).

In Agile, projects are divided into small, managable units of work called "sprints" or "iterations". Each sprint usually lasts one to four weeks and involves planning, development, testing and reviewing. Having sprints allow teams to produce higher quality of work faster and more frequently whilst being able to receive regular feedback and make necessary adjustments and improvements (Max Rehkopf, n.d.).

<b>Implementing Agile for an API project</b>

<u>Ideation</u>

1. Planning: Involves breaking down the project into smaller and manageable increments, prioritising certain tasks and engaging with stakeholders to set the foundations of the project.

   - Vision: e.g. to develop a scalable API for an e-commerce website to enhance user expierience and increase sales.
   - Goals: e.g. Implement functions such as product management and order processing and provide comprehensive API documentation.
   - Engage Stakeholders: Identify and gather information regarding stakeholder requirements and expectations.
   - Create backlog: Compile a detailed list of user stories and tasks required to complete the project. E.g., Create user authentication, product management, order management and payment processing.

2. Scope Definition: An important phase in project management where the project's boundaries, deliverables and requirements are explicitly outlined and agreed upon. This ensures that all stakeholders have a clear understanding of what the project can and cannot achieve.

3. Forming Agile Team: A cross-functional team is needed in order to deliver the project. Each role contributes to the different aspects of the project from the developement to testing.

   e.g. Team composition for API project:

   - Developers
   - Testers
   - Product Owner
   - Scrum Master

4. KickOff Meeting: This meeting sets the foundation of the project, ensuring that everyone understands the goals, timeline and tools for the project. This establishes clear communication pathways.
   What typically happens in these meetings:
   _ Team members introduce themselves and their roles.
   _ The project objective's, scope and requirements are discussed, \* The timeline of the project is outlined.

<u> Development and Testing </u>

1. StandUps: Daily standups assist the team to stay on top of their work, share progress and quickly address any issues. Standups are ideally held daily and each team member briefly discusses what they are doing and did the day before all the while the scrum master takes notes.

2. Development: Developers will focus on delivering small increments of work so that it can be reviewed and tested regularly.

3. Testing: Continuous integration is implemented to automatically build and test the API with each change. This allows the new features to integrate seamlessly.

<u> Sprint Review </u>

1. Sprint Review: After each sprint, a sprint review meeting is held where the team shows their completed work to stakeholders and gathers feedback. After this meeting, a retrospective meeting is held to reflect upon the sprint and to discuss what worked and what didn't and what the team could improve on in future sprints.

Other important practices that the team must do in order to have a sucessful project is:

- Create and provide ckear and comprehensive documentation for the API.
- Utilising tools like Jira and Trello for task managment, and Slack or Teams for real-time communication.
- Monitor performance and regularly provide and receive feedback.
- Be able to regularly review and adapt Agile practices.
- Encourage and enable team members to continuously learn and improve their skills.

---

### Q4.

Source control, often also reffered to as version control, is the practice of managing and tracking codes and files over the duration of a project. This practice allows multiple developers to collaborate whilst keeping a history of changes.

A standard source control for an API project can look like this:

1. Initial setup:

   - Creating a repository: A repository is a centralised location where the code and its history is stored. It can be hosted locally or on platforms like GitHub. After a repository is created, it is initialised with a 'README.md" file.
   - Defining branching strategy: A branch in a parallel version of the codebase and there are different branching strategies. Typically, developers will have a 'main' branch that is production-ready and a 'develop' branch for ongoing development.

2. Developing Features:

   - For all new features that are created and bugs that are fixed, a new branch is created and named respectively.
   - Making changes: Ensure that changes are commited frequently with clear messages and documentation.

3. Code Review:

   - Open a pull request: Once features are completed by on its respective branch, a pull request is created to merge the code into the develop branch. Pull requests should include detailed description of the changes and any other relevant information. Team members then review the code in the pull request, provide feedback and or approve of the changes.

4. Merging
   - After the code is reviewed successfully and pass all testing, the feature branch is then merged into the develop branch, then the feature branch is usually deleted after merging. Once code is merged into the developing branch, further tests are ran to ensure that all features work together.
     Finally, when the develop branch reaches a stable point with all the features, a release branch is created, tested and then merged into the main branch.

---

### Q5.

---

### Q6.

Information system security is the important practice of protecting information systems from threats. The three core principles of information system security is <b> confidentiality, integrity and availability of data</b> (Fortinet, n.d.).

<b>Confidentiality:</b> Confidentiality ensures that sensitive information can only be accessed by those authorised to view it. This process involves protecting data from unauthorised access and ensuring that only intended users can access and handle the information. A common method that this principle is carried out is through encryption. This is used commonly when people use online banking, where their important and sensitive financial data is encrypted to ensure that only the bank account owner and the back can access it. (NIST, 2020)

<b>Integrity:</b> Integrity refers to the accuracy of information. This core principle makes certain that data cannot be tampered with by unauthorised parties or processes. Database integrity constraints often used to uphold integrity. These are rules that are applied to databases to ensure the accuracy and consistency of data (RiskXchange, 2023). Weak integrity of data can have severe reprecussions for everyone, for example, hackers being able to steal credit card information by accessing bank databases illegally.

<b>Availability:</b> Availability ensures that information can be readily accessed by authorused users. An example method that is used to ensure information availibility is by using redundant systems. For example, a company may use multiple servers in various locations to ensure that if one server fails, another can be utilised, without any downtime and maintaining constant access to users.

---

### Q7.

Implementing the principle of availability in an API project involves ensuring that the API is accessible and functional when needed, with minimal performance issues and downtime. Practices that ensure high availability are:

1.

---

### Q8.

In Australia, developers of social media websites and applications many legal oblications to uphold when handing user data. These obligations are governed by the Privacy Act 1988 (Cth) and its associated Australian Privacy Principles (APPs) (Federal Register of Legislation, 2022).

The Australian Privacy Princuples (APPs) have 13 set principles that provide the necessary framework for handing personal information.

The principles and how they relate to social media are as listed:

1. APP 1 - Open and Transparent Management of Personal Information: Developers must be transparent in the way they handle users' personal information. They must provide clear and up-to-date privacy policies that outline how they handle information.
2. APP 2 - Anonymity and pseudonymity: Users must have the option to remain anonymous or use a pseudonym when using social media services. e.g. When creating an account on a social media website, users are not required to provide their real names unless it is required by law.
3. APP 3 - Collection of Solicited Personal Information: Developers can only collect information that is reasonably necesssary for the platform's operation.
4. APP 4 - Dealing with Unsolicited Personal Information: Organisations must destroy information that it did not solicit. This principle ensures that organisations do not keep unecessary personal information of users.
5. APP 5 - Notifcation of the Collection of Personal Information: Users must be informed about the collection of their information. The purpose of collection and any third party information but be disclosed along with their rights regarding the information.
6. APP 6 - Use or Disclosure of Personal Information: Users' personal information is only allowed ot be used or disclosed for the primary purpose for which it was collected for.
7. APP 7 - Direct Marketing: Personal information can't be used for direct marketing unless the user has consented.
8. APP 8 - Cross-border Disclosure of Personal Information: If personal information is used overseas, the developer must ensure that the international recipient complies with the privacy laws.
9. APP 10 - Quality of Personal Information: Developers must ensure that personal information they collect and use is accurate and up to date.
10. APP 11 - Security of Personal Information: Developers must take reasonable steps to protect personal information and prevent it from misuse, interence, loss and unauthorised access.
11. APP 12 - Access of Personal Information: Developers must allow users to have the right to access the personal information that is held about them.
12. APP 13 - Correction of Personal Information: Developers must take reasonable steps to correct personal information to ensure it is accurate.

As for beyond Australia, In the United States, social media website and application developers must comply with the Children's Online Privacy Protection Act (COPPA), which requires parental consent for collecting data from children under the age of 13. They must also follow the California Consumer Privacy Act (CCPA), which grants Californian residents rights to access, delete and opt out of the sale of their information. Additionally, developers handling data from users from the European Union must follow the General Data Protection Regulation (GDPR), which has strict consent and data protection measure mandates.

---

### Q9.

---

### Q10.

---

### Q11.

---

### Q12. Spotify

<b>1.</b> Spotify is one of the world's leading music streaming service. Here is a list of the many technologies that are utulised to build and operate the application:

- Frontend:
  - JavaScript: The main language for developing Spotify's web applications.
  - React: A JavaScript library used for building user interfaces.
  - Sass: A scripting language that is used to generate CSS for styling its web application.
