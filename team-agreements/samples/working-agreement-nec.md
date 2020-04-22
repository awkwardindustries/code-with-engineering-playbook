# Working Agreement

## Goal

This living document represents the principles and expected behavior of everyone involved in the project. It is not meant to be exhaustive nor  complete. The team should be accountable to these standards and revisit, review, and revise as needed. The agreement is signed off by everyone.

## Code of Conduct

We pledge to follow the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/):

* **Be friendly and patient**: Remember you might not be communicating in someone else's primary spoken or programming language, and others may not have your level of understanding.
* **Be welcoming**: Our communities welcome and support people of all backgrounds and identities. This includes, but is not limited to members of any race, ethnicity, culture, national origin, color, immigration status, social and economic class, educational level, sex, sexual orientation, gender identity and expression, age, size, family status, political belief, religion, and mental and physical ability.
* **Be respectful**: We are a world-wide community of professionals, and we conduct ourselves professionally. Disagreement is no excuse for poor behavior and poor manners. Disrespectful and unacceptable behavior includes, but is not limited to:
  * Violent threats or language.
  * Discriminatory or derogatory jokes and language.
  * Posting sexually explicit or violent material.
  * Posting, or threatening to post, people's personally identifying information ("doxing").
  * Insults, especially those using discriminatory terms or slurs.
  * Behavior that could be perceived as sexual attention.
  * Advocating for or encouraging any of the above behaviors.
* **Understand disagreements**: Disagreements, both social and technical, are useful learning opportunities. Seek to understand the other viewpoints and resolve differences constructively.
* This code is not exhaustive or complete. It serves to capture our common understanding of a productive, collaborative environment. We expect the code to be followed in spirit as much as in the letter.

## How we plan together

### Work Items

* We will track our work in Azure DevOps
* Our sprint work items will follow the hierarchy:
  * Epic
    * Feature
      * Story
        * Task
      * Bug
        * Task
* We will track Risk work items outside of the hierarchy so that we may easily manage them independently; however, we may choose to relate them to other work items.

|  | Sizing | Definition |
|--|--------|------------|
| **Epic** | Up to the lifetime of the project | Business initiative for a stakeholder to accomplish |
| **Feature** | Completable within 2-3 sprints | Collection of stories representing a slice of value for the stakeholder |
| **Story / Bug** | Completable within a sprint | Atomic unit of value for the project as engineering team |
| **Task** | Completable within a day | Optionally defined by the story owner to help track work that must be completed to consider a story done |
| **Risk** | N/A | Something that the team would like to shine light on to ensure actions can be taken to mitigate effects on the project |

#### User Story Guidelines

> Sourced from <https://www.scrumtraining.com>

##### User Story Guideline

   As *[Role]* I can *[Feature/Function]* so that *[Goal/Business Value]*.

##### Acceptance Criteria/Tests

   User can *[select/operate] [Feature/Function]* so that *[output]* is *[visible/complete/etc.]*  
   Verify that...

##### I.N.V.E.S.T. in User Stories

<u>**I**</u>ndependent - Can it be developed independently of other stories?  
<u>**N**</u>egotiable - Is the scope negotiated to enable completion?  
<u>**V**</u>aluable - Is the value to the user or customer clear?  
<u>**E**</u>stimatable - Can the work be estimated? Are there unknowns, dependencies, barriers? Do we lack domain or technical knowledge?  
<u>**S**</u>ize appropriately - Can it be completed in the iteration?  
<u>**T**</u>estable - What are the tests to know the work is done?

##### User Story Issues to Avoid

* Describing a task
* UI too soon
* Write in an inactive voice
* Splitting too often in the iteration
* Thinking too far ahead
* Interdependent Stories
* Too many details
* Goldplating
* Stories are too small

#### Definition of Ready

* User stories clearly provide context and scope of work
* Acceptance Criteria is defined
* User stories are achievable in a single sprint (else break it down)
  * "Spike" if investigating something in order to timebox and track outcomes
* Story owner is able to break down user story into tasks if desired
* Dependencies identified (either external or other work items)

#### Definition of Done

* Acceptance Criteria are satisfied
* Appropriate [Pull Request template(s)](../../.azuredevops/) satisfied
* [Pull Request](#pull-requests) approved and completed
* Demonstration recorded and available to customer (when applicable)

### Backlogs and (Dash)boards

* Product Owner owns the Product Backlog (Epics/Features/Stories/Bugs).
* Tech Lead owns the Risk Backlog.
* Story Board will be used to track project progress.
  * Story Board columns:
    * **New**: Any User Story or Bug can be created and captured here. There are no requirements for items in this status as they will be groomed and moved to the **Ready** column once they are ready for the development team.
    * **Ready**: Has been groomed and meets our [Definition of Ready](#definition-of-ready).
    * **Committed**: The development team has committed to completing these stories or bugs within the next sprint.
    * **In Progress**: A development team member owns the story or bug and begins work.
    * **In Review**: The owner of the story or bug determines the item meets our [Definition of Done](#definition-of-done) and has created a Pull Request. The item will stay in this status through the PR process -- including addressing requested feedback or fixing issues found.
    * **Closed**: The Pull Request has completed, and the work has been committed to the `master` branch of the project repository.
  * Story Board styles:
    * We will style stories or bugs that have been committed to the current sprint so that they may be easily identified from the story board.
    * We will style stories or bugs that were committed to the previous sprint but carried over so that we may focus on completing the items as soon as possible to reduce impact on the current sprint.
* Dashboards will be utilized to support summary-level views of the project to different audiences.

### Estimating

* We will estimate Stories and Bugs with story points to help gauge how much we work we commit to within a sprint.
* We will use 1, 3, 5, or 10 for our story points -- with one being small, three being about half a sprint, five being a full sprint, and ten being something too big that needs to be broken down to fit within a single sprint.
* Tasks will not require hour estimates as we will track our progress at the story/bug level.

### Ceremonies

* Our sprints will be one week and run from Wednesday to Wednesday with Review, Retrospective, and Planning occurring back-to-back.
* We will use an assigned Scrum Master versus rotating the role among the team.

|  | When | Length | Participants | Purpose |
|------|------|--------|--------------|---------|
| **Grooming** | Mondays @ 10:00am PST | 45 minutes | Scrum Master, Product Owner, Tech Lead | Ensure at least two sprints worth of work is Ready in the Backlog. |
| **Planning** | Wednesdays @ 10:30am PST | 60 minutes | Scrum Master, Product Owner, Development Team | Commit to work for the next sprint. |
| **Scrum / Standup** | Monday, Tuesday, Thursday, Friday @ 11:00am PST | 15 minutes | Development Team, Scrum Master, Product Owner | Those with committed work answer: What did I do yesterday? What will I do today? Is there anything in my way? |
| **Review** | Wednesdays @ 9:00am PST | 45 minutes | Development Team, Scrum Master, Product Owner | Demonstrate the work we did this week. Show and tell time. |
| **Retrospective** | Wednesdays @ 9:45am PST | 45 minutes | Development Team, Scrum Master, Product Owner | Reflect as a team on how we're doing -- what's working well for us, and what could we do better? |

## How we code together

### Branch Strategy

* `master` branch will be used
  * It will be locked, requiring a PR to make commits.
  * It will be shippable at any time.
* Branches will be used for story or bug-fix work.
  * Naming convention will include using either the `feature/` or `bugfix/` foldering prefix to a short description of the story or bug (e.g., `feature/create-working-agreement` or `bugfix/deploy-script-error-on-box`). Avoid using the work item IDs in your branch names.
  * If multiple developers have commits for the same story, they should share the story branch versus creating user-specific branches in order to deliver a single unit of value upon PR completion.
  * Commits should always have a short but descriptive message explaining what is changing.

### Versioning & Tagging

* Deliverable does not require versioning since we do not anticipate supporting multiple releases side-by-side.
* Build numbers will be used to help us track deployments versus versions.
* We will tag as needed to identify milestones along master branch.

### Reviews

* While Pull Requests will be required as an official form of review for any work done, informal ad-hoc code reviews or design reviews are encouraged.
* Designs that may impact other areas or assumptions should be informally reviewed with a larger audience (preferably including the project leads) for visibility to the proposed changes and feedback.

### Pull Requests

* PRs should capture all of the work required to deliver a story or bug fix. Prefer a single PR to close a story over multiple PRs that deliver incomplete value.
* PRs should contain complete descriptions that follow the template and describe the scope of the work and how it meets the acceptance criteria if not obvious.
* A branch policy that requires the PR is tied to a user story or bug is in place.
* A branch policy that requires two approvers to complete a PR is in place. Add the entire team (using a group) to the PR for review, but explicitly call out the approvers as named reviewers. Ask for committed approvers early (consider asking at assignment), and as a committed approver attempt to complete within a day of assignment. If you don't feel you are a qualified approver, comment on that, remove the explicit reviewer assignment to yourself and try to find another approver to replace you.
* A branch policy that requires a successful and unexpired merge build before completion is in place.
* A branch policy that requires all PR comments to be resolved is in place.
* Linters must pass before completion. (Note: not all file types will require linting.)
* Tests must pass before completion.
* PRs will utilize a squash merge into master upon completion ensuring a linear commit history with a single consolidated commit per PR.
* Branches will be deleted after PR completion -- missed functionality should be captured as a new bugfix or story.

### Pairing

Pairing work is recommended to support knowledge sharing between the team members. Work items have a dedicated field *Pairing with* so that a second team members is explicitly assigned. Each team member should look for pairing opportunities before picking up a new work item. Commits should be made by the people that are assigned to the story. Other team members are encouraged to provide feedback using PR comments.

## How we track and share information

* We will prefer our Teams General Channel for discussions or questions over email.
* We will use Teams for meetings and calls
* We will make documentation accessible:
  | Type | Where? | Examples |
  |------|--------|----------|
  | Organization Artifacts | Teams Channel Files | Game Plan, SDD, draft documents |
  | Project Artifacts | Teams Channel Files | ADS agenda, Sprint Review videos, Meeting Notes |
  | Project Documentation | Azure DevOps Repo | Working Agreement, code of conduct, high-level overview |
  | Architecture / Designs | Azure DevOps Repo | Technical Design documents |