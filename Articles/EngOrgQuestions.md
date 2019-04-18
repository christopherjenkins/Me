# Engineering Operational Maturity Matrix

Below are questions I like to ask to assess the overall maturity of an engineering organization. Not all questions are valid for every scenario. When teams are small a lot of these questions won't be valid. These questions help to clarify engineering's role in a broader org, the control they are allowed to exert in an org, and if it's a good environment to work in. 

## Process

### Product/Project
* Are there dedicated product/solution owners?
* Are product owners attached to specific teams or are they a functional team?
* Does product regularly engage in gathering user feedback?
* Do teams hold regular daily meetings?
* Do teams work in sprints and observe typical sprint ceremonies (planning, demo/retro)
* Do team members commit to reasonable amounts of work, or are they pressured to overcommit? 
* Who sets due dates?
* Is velocity consistent?
* Are there dedicated Project Managers?
* Are engineers consulted in project planning?
### QA/Test/UAT
* Is there dedicated QA in a reasonable ratio of eng to qa? (1:5 min) 
* Is QA attached to a scrum team or are they a functional separate team?
* Does QA do test automation? Manual Regressions? Combination of both?
* Do engineers write unit tests? What is overall test coverage?
* Load/Stress Testing on API and bottlenecks?
* Do engineers consider testing a core part of their job?
* Do we conduct User Acceptance Testing? What is the process & who participates?
### Engineering
* Do engineers have everything they need to complete a unit of work before beginning?
* Are engineers encouraged to collaborate?
* Are there regular pair programming sessions?
* Do engineers conduct thorough peer code reviews?
* Are engineers committed to the organizational process?
* Do engineers have the ability to push back on product reqs or imposed deadlines?
* Are engineers given enough whitespace to work out difficult problems and engage in continued learning?
### DevOps
* What does the gitflow look like?
* Are there automated build & release pipelines for all environments?
* Disaster Recovery & Backups for DB State?
* Are there proper permissions setup for production environments?
* Are all builds also tested?
* How long would it take you to recover from a cloud provider critical outage requiring you to move everything?
* Have we identified areas of vendor lock-in? (not bad, but should know)
* Secret/Key security policies in place?
* APM, Infrastructure monitoring, on-call hours?
### CX
* Do we have dedicated sales engineers / subject matter experts of our products?
* Do we have dedicated, tiered support mechanisms?
* Is there an onboarding team?
* Do we have customer facing documentation? (if required)
### UI/UX
* Is there a dedicated UI/UX team? 
* Does UI/UX engage in user testing and feedback?
* Are there tools to allow them to A/B test?
* Does UI/UX scrum with engineering?
* Are there dedicated resources for each initiative?
### Executive Support
* Do executives support engineering initiatives? 
* What is the role of engineering in the organization?
* Is engineering viewed as a critical component or a necessary evil?
* Do executives override product goals or engineering timelines regularly?
* Is there a defined budget for engineering initiatives?
* Do we understand how engineering contributes to company revenue results?
* Does engineering have executive representation on par with others in the organization?

## People

### Feedback (Peer, Manager, Employee)
* Does the environment foster continuous feedback between everyone in the company?
* Are feedback/discipline items handled swiftly and directly? 
* Are employees given an opportunity to give feedback to managers?
* Are team members able to be critical without fear?
* Are team members given regular feedback from their managers?
### OKR's & Clearly Defined Targets
* Does the company regularly engage in goal setting and ensure that everyone is aligned?
* If I sampled a set of team members, would they all be able to answer what their goal was? 
* Do individual goals align with team goals or do they get out of sync?
* How are people held accountable to completion of work items?
* Does the company regularly hit their targets? why or why not?
### Roles & Responsibilities
* Does everyone have a clearly defined role?
* Do they understand how their responsibilities positively impact the company?
* Does everyone have an accurate Job description?
* Do team members understand what is required for them to progress in the organization?
### Interviews, Candidates
* Are interviews consistent and as unbiased as possible?
* Do you have a lot of difficulty filling open reqs? 
* How many applicants do you get on average before filling a role?
* What is the eng churn rate? Reasons for leaving?
### Office Environment
* Are eng teams given quiet places to work and think through difficult problems?
* Does the company support remote jobs?
* Does the company sponsor visa employees?
* Flexible working hours?
* Easy access to other people, lots of meeting rooms?
* Dedicated offices, shared offices, open office?
* What other teams are physically located near the engineering team?
### Engineering Tools
* Do engineering teams get to choose the right tool for the job? 
* Are engineers allowed a budget and freedom to choose hardware and software?
### Fun
* Does the team enjoy working here?
* Does the team get to celebrate milestones? Are they rewarded for extra effort?
* Is the team inclusive and nice to new team members?
* Is the team proud of the work they do?

## Disciplines

### Security / Compliance
* Is there a compliance team? 
* Who handles overall security in the org?
* Who oversees security in the products that are released?
* Are there risk models and breach policies in place?
* Are there policies for handling legal requests?
* Do we have access to legal to validate compliance?
* Are there functional owners for security overall?
### Build / Test / Release
* Who is responsible for DevOps in the organization?
* Are build, release, rollback, incident management guidelines documented and published?
* Do we regularly run failure scenarios?
### Architecture & Design
* What is the overall software architecture design from a high level?
* Is there an accounting of all dependencies for this architecture?
* Who is currently responsible for keeping everyone aligned in this architecture?
* What are the pros/cons of the current design?
* Is it scalable/sustainable for our future plans?
### Support
* Do we have dedicated support staff for our customers?
* What are the published guidelines for response times and incident management?
* Does support have access to tools to help them solve problems, or are they directly reliant on engineering?
### Stability
* Do we have published guidelines for SLA's?
* Are our customers happy with the current stability of the platform?
* Are we in a position to handle large changes/fluctations in resource needs?
* Are we prepared for catastrophic failures?

