# W05 Group Project Checkpoint

## Meeting Summary

**Meeting time:** Wednesday at 6:00 PM MST (UTC−7)  
**Week 05 group leader:** Lucky Ayeni Inyang Eni  
**Proposed Week 06 group leader:** Emmanuel Kalanda Owilli

### Participants

- Victor Chavez
- Stephen Sanders
- Lucky Ayeni Inyang Eni
- Emmanuel Kalanda Owilli

The meeting opened with prayer. The team reviewed the StudySync repository, the Week 04 checkpoint, and the Trello board. We discussed the difference between completed foundation work and the remaining design and implementation work. The group kept the seven approved user stories and the current minimum viable product scope because they remain realistic for the semester.

The team agreed to continue using the Trello workflow of Product Backlog, Ready, In Progress, Review / Testing, and Done. Tasks should move as work begins and should include an owner, deliverables, and acceptance criteria. The immediate priority is to finish the domain model, responsive wireframes, and Identity integration plan before beginning database migrations and full feature development.

## Group Activity During the Week

### Successes

- The shared GitHub repository and .NET 9 Blazor application remain available to the team.
- The repository now includes contribution instructions, branch-naming guidance, and a pull-request workflow.
- The README identifies the project status and links to the proposal and checkpoint documents.
- The project builds successfully with zero warnings and zero errors.
- The Trello board contains seven approved feature cards and four documented implementation tasks.

### Challenges

- The first implementation tasks depend on agreement about the domain model and authentication approach.
- The team must keep Trello status current so the board reflects actual work rather than only planned work.
- Large feature cards still need to be divided into smaller development and testing tasks.
- Parallel work must be separated by branch to reduce merge conflicts.

### Planning Adjustments and Change Orders

- No features were added to the minimum viable product this week.
- Database migrations will wait until the team reviews the initial domain model.
- Authentication implementation will begin after the Identity plan identifies packages, persistence, protected routes, and authorization rules.
- UI implementation will follow the responsive discovery and dashboard wireframes.
- Each contributor should keep only one primary card in **In Progress** and move completed work to **Review / Testing** before **Done**.

## New and Continuing Tasks

### Victor Chavez

- Maintain repository and workflow documentation.
- Verify clean restore and build instructions.
- Keep project links and weekly checkpoint documents current.

### Stephen Sanders

- Complete the initial domain model for Course, StudyGroup, GroupMembership, StudySession, and SessionRegistration.
- Document keys, required fields, and relationships for team review.

### Lucky Ayeni Inyang Eni

- Complete responsive wireframes for group discovery and the personal dashboard.
- Identify reusable components and mobile, empty, and error states.

### Emmanuel Kalanda Owilli

- Complete the ASP.NET Core Identity integration plan.
- Document required packages, database changes, protected routes, and ownership authorization.

## Personal Task Report — Victor Chavez

### Task

**Document the solution structure and development workflow.**

### Work Completed

I documented how contributors can clone, restore, build, and run the StudySync Blazor application. I added branch-naming conventions for feature, fix, documentation, and refactoring work, along with expectations for descriptive commits, pull requests, and teammate review. I also kept the README project status and links current and verified the solution build.

### Function and Fit Within the Project Scope

This task provides the collaboration foundation for the entire StudySync project. It does not add a user-facing feature, but it helps all four contributors work consistently in the same repository, reduces merge conflicts, and creates a repeatable review process. This directly supports every feature in the approved scope because account management, study groups, discovery, sessions, and the dashboard will all be developed and reviewed through this workflow.

### Evidence

- [Contribution and development workflow](../CONTRIBUTING.md)
- [Project README and status](../README.md)
- The .NET solution builds with zero warnings and zero errors.

## Project Links

- **Trello Board:** https://trello.com/b/DHl8Xd43/cse-325-group-project
- **GitHub Repository:** https://github.com/VictorChavez0501/CSE325-Group-Project
- **Week 04 Checkpoint:** [W04-PROJECT-CHECKPOINT.md](W04-PROJECT-CHECKPOINT.md)

## Submission Checklist

- [x] Group meeting and weekly activity summarized.
- [x] Challenges, successes, continuing tasks, and planning adjustments included.
- [x] Live meeting participants listed.
- [x] Trello board URL included.
- [x] Victor's personal task described with its function and relationship to project scope.
