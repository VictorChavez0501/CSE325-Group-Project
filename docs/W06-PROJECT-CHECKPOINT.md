# W06 Group Project Checkpoint

## Meeting Summary

**Meeting time:** Wednesday at 6:00 PM MST (UTC−7)  
**Week 06 group leader:** Emmanuel Kalanda Owilli  
**Proposed Week 07 group leader:** Victor Chavez

### Participants

- Victor Chavez
- Stephen Sanders
- Lucky Ayeni Inyang Eni
- Emmanuel Kalanda Owilli

The meeting opened with prayer. Each member reported on the task assigned during the previous checkpoint. The team reviewed the current StudySync application, the seven approved user stories, the Trello workflow, and preparation needs for the final submission. The repository and application foundation are stable, but the group identified persistence and authentication as the most important unresolved technical risks.

The group decided to freeze the scope and avoid adding new features. Final work will focus on completing and integrating the most demonstrable parts of the approved minimum viable product, verifying responsive behavior, and preparing a clear video demonstration in which every team member explains an individual contribution.

## Weekly Activity and Progress

### Successes

- The .NET 9 Blazor application continues to build with zero warnings and zero errors.
- Contribution instructions and weekly project records remain available in the repository.
- A functional group-discovery page was added to the application.
- Users can search groups by course, name, topic, or location.
- Users can filter results by in-person, online, or hybrid meeting format.
- The page communicates result counts, full-group status, and an empty state.
- The homepage and navigation now link to the functional prototype.

### Challenges and Concerns

- No merged repository evidence currently confirms completion of persistent data storage.
- Authentication and authorization are not yet implemented in the shared `main` branch.
- Several feature cards remain larger than can safely be finished and tested before the final deadline.
- The team must coordinate final contributions quickly and avoid conflicting changes.
- A video cannot be recorded until the final demonstration flow is stable and every member has an assigned speaking role.

### Change Orders

- The feature scope is frozen; no new user stories will be added.
- Group discovery is the primary functional workflow for the current demonstration build.
- Final changes must be small, reviewable, and directly tied to an approved feature or submission requirement.
- The team will clearly distinguish implemented behavior from planned behavior during the demonstration.
- Any unfinished persistence or authentication work will be reported honestly rather than simulated as complete.

## Member Task Reports and Final Assignments

### Victor Chavez

**Reported work:** Implemented and integrated the interactive group-discovery prototype, updated navigation and project status, maintained checkpoint documentation, and verified the build.

**Final assignment:** Test the discovery workflow, keep `main` buildable, update final links, and lead the application portion of the video.

### Stephen Sanders

**Continuing task:** Complete the initial domain model and submit the entities and relationships for review.

**Final assignment:** Integrate the reviewed model if ready and explain how it supports groups, memberships, sessions, and registrations.

### Lucky Ayeni Inyang Eni

**Continuing task:** Complete responsive wireframes and document reusable components and edge states.

**Final assignment:** Perform desktop/mobile usability checks and help organize the final demonstration sequence.

### Emmanuel Kalanda Owilli

**Continuing task:** Complete the ASP.NET Core Identity integration plan.

**Final assignment:** Identify the safest authentication work that can be completed and tested before submission and explain the security approach in the video.

## Personal Task Report — Victor Chavez

### Task

**Build the StudySync group-discovery prototype.**

### Description and Function

I created a new interactive Blazor page that displays available study groups and allows users to search by course, group name, topic, or location. I also added a meeting-format filter for in-person, online, and hybrid groups. The page updates the result count, indicates when a group is full, and provides a clear empty state with a control to reset the filters. I connected the page to the main navigation and changed the homepage call to action so users can reach the working feature.

### Fit Within the Project Scope

Group discovery is one of StudySync's seven approved core features. It addresses the central project need: helping college students find relevant study groups. The implementation demonstrates Blazor component state, event handling, conditional rendering, responsive layout, and accessible feedback while remaining inside the semester MVP. The current data is sample data, so persistent storage and authenticated membership actions remain final-stage work rather than being represented as complete.

### Evidence

- [Group discovery component](../CSE325GroupProject/Components/Pages/Groups.razor)
- [Responsive group discovery styles](../CSE325GroupProject/Components/Pages/Groups.razor.css)
- [Application navigation](../CSE325GroupProject/Components/Layout/NavMenu.razor)
- Verified build: zero warnings and zero errors.

## Video Demonstration Plan

The team plans to record together during the regular Wednesday meeting at 6:00 PM MST (UTC−7). Every team member will have a speaking role. The demonstration will introduce the problem and scope, show the repository and collaboration process, run the application, demonstrate the group-discovery workflow, explain the data and security approach, and state remaining limitations. Detailed preparation steps are in [W07-FINAL-SUBMISSION-PLAN.md](W07-FINAL-SUBMISSION-PLAN.md).

## Project Links

- **Trello Board:** https://trello.com/b/DHl8Xd43/cse-325-group-project
- **GitHub Repository:** https://github.com/VictorChavez0501/CSE325-Group-Project
- **Final Submission Plan:** [W07-FINAL-SUBMISSION-PLAN.md](W07-FINAL-SUBMISSION-PLAN.md)

## Submission Checklist

- [x] Meeting and weekly activity summarized.
- [x] Successes, challenges, tasks, and change orders included.
- [x] Participants listed.
- [x] Trello URL included.
- [x] Personal task described with its function and fit within project scope.
- [x] Final assignments and video plan documented.
