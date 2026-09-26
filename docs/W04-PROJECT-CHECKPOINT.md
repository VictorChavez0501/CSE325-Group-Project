# W04 Group Project Checkpoint

## Meeting Summary

**Meeting time:** Wednesday at 6:00 PM MST (UTC−7)  
**Week 04 group leader:** Stephen Sanders  
**Proposed Week 05 group leader:** Lucky Ayeni Inyang Eni

### Participants

- Victor Chavez
- Stephen Sanders
- Lucky Ayeni Inyang Eni
- Emmanuel Kalanda Owilli

The meeting opened with prayer. The team discussed lessons and challenges from this week's .NET work and reviewed the current StudySync application, GitHub repository, Week 03 proposal, and Trello board. The team confirmed that StudySync remains appropriately scoped for the semester and that the seven core user stories still describe the intended minimum viable product.

The group reviewed the distinction between product features and implementation tasks. Feature cards describe value delivered to users, while task cards describe the smaller technical and design activities required to complete those features. The team agreed to keep feature cards in the Product Backlog and move selected implementation tasks through Ready, In Progress, Review / Testing, and Done.

## Progress Since the Previous Checkpoint

### Completed

- Created and published the shared GitHub repository.
- Created the .NET 9 ASP.NET Core Blazor application.
- Selected **StudySync: Campus Study Group Coordinator** as the final project.
- Completed the formal Week 03 project proposal.
- Defined the minimum viable product and its out-of-scope boundaries.
- Added seven core feature cards and user stories to the Trello Product Backlog.
- Replaced the default Blazor landing page with StudySync branding and a responsive proposal overview.
- Verified that the solution builds with zero warnings and zero errors.

### In Progress

- Drafting the initial domain model and relationships.
- Planning ASP.NET Core Identity integration.
- Designing responsive wireframes for group discovery and the personal dashboard.
- Defining acceptance criteria and validation rules for the first feature set.

### Current Risks and Adjustments

- **Risk: Features are too large to complete as single work items.** Each feature will be divided into smaller implementation and testing tasks before development begins.
- **Risk: Authentication could delay other work.** Identity setup will be researched and implemented early, while UI and domain-model tasks proceed independently.
- **Risk: Contributors could edit the same files simultaneously.** Each member will work on a separate branch and open a pull request for review before merging.
- **Adjustment:** The first iteration will focus on project architecture, data design, authentication planning, and two essential user interfaces instead of attempting all seven features at once.

## Trello Work-Item Approach

The team will use the board lists as follows:

- **Project Ideas:** Original alternatives retained for historical context.
- **Product Backlog:** Approved features and user stories that may span multiple tasks.
- **Ready:** Small, documented tasks that have an owner and acceptance criteria.
- **In Progress:** Tasks actively being completed. Each member should have no more than one primary task here at a time.
- **Review / Testing:** Work awaiting code review, functional verification, or acceptance testing.
- **Done:** Work that satisfies its acceptance criteria and has been merged or formally approved.

Every implementation card should include a concise description, an owner, acceptance criteria, and references to the related feature or pull request when available.

## Individual Assignments

### Victor Chavez — Repository and Application Foundation

**Primary task:** Document the solution structure and development workflow.

**Deliverables:**

- Add contribution and branch-naming guidance to the repository.
- Verify the application builds from a clean checkout.
- Keep README status and project links current.

**Acceptance criteria:** A new contributor can clone, build, run, and understand the project workflow using repository documentation.

### Stephen Sanders — Domain Model

**Primary task:** Draft the initial domain entities and relationships.

**Deliverables:**

- Define Course, StudyGroup, GroupMembership, StudySession, and SessionRegistration entities.
- Document primary keys, required fields, and relationships.
- Present the model for team review before database migrations are created.

**Acceptance criteria:** The model supports all seven approved user stories without including out-of-scope functionality.

### Lucky Ayeni Inyang Eni — Responsive Wireframes

**Primary task:** Design the group-discovery and personal-dashboard interfaces.

**Deliverables:**

- Produce desktop and mobile wireframes for both screens.
- Identify reusable UI components and empty/error states.
- Add screenshots or links to the relevant Trello cards.

**Acceptance criteria:** The wireframes show the information and actions required by the approved user stories at desktop and mobile widths.

### Emmanuel Kalanda Owilli — Authentication Plan

**Primary task:** Research and document ASP.NET Core Identity integration.

**Deliverables:**

- Recommend the Identity configuration for the current Blazor application.
- Identify required packages, database changes, and protected routes.
- Document registration, login, logout, and ownership-authorization requirements.

**Acceptance criteria:** The team has a reviewed implementation plan that stores passwords securely and protects authenticated operations.

## Team Working Agreements

- Create a separate Git branch for each task.
- Use descriptive commits and reference the corresponding Trello card.
- Open a pull request before merging feature work into `main`.
- Require at least one teammate to review meaningful code changes.
- Move cards as work progresses rather than updating Trello only at the weekly meeting.
- Communicate blockers early so tasks can be adjusted before the deadline.

## Project Links

- **GitHub Repository:** https://github.com/VictorChavez0501/CSE325-Group-Project
- **Trello Board:** https://trello.com/b/DHl8Xd43/cse-325-group-project
- **Week 03 Proposal:** [W03-PROJECT-PROPOSAL.md](W03-PROJECT-PROPOSAL.md)

## Checkpoint Checklist

- [x] Meeting content summarized.
- [x] Participants listed.
- [x] Current progress documented from repository evidence.
- [x] Trello work-item workflow agreed upon.
- [x] Each team member assigned a specific task.
- [x] Risks and planning adjustments documented.
- [ ] Publish the individual task cards to Trello.
- [ ] Confirm Lucky Ayeni Inyang Eni as the Week 05 group leader.

