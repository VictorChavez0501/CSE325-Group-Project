# W03 Group Project Proposal

## Meeting Summary

**Meeting time:** Wednesday at 6:00 PM MST (UTC−7)  
**Week 03 group leader:** Victor Chavez  
**Next group leader:** [Confirm the name selected by the group]

### Participants

- Victor Chavez
- Stephen Sanders
- Lucky Ayeni Inyang Eni
- Emmanuel Kalanda Owilli

The meeting opened with prayer. Team members discussed their challenges and discoveries from this week's .NET and Blazor learning activities, including component organization, routing, data binding, dependency injection, and maintaining a shared project with GitHub. The group also reviewed the five ideas generated during the previous meeting and considered their value, technical complexity, target audiences, and feasibility within one semester.

The group selected **StudySync: Campus Study Group Coordinator** as its semester project. The team defined a realistic minimum viable product, identified the features that are inside and outside the semester scope, considered the application's data and security requirements, and translated the core features into user stories suitable for the Trello backlog.

## Project Title

**StudySync: Campus Study Group Coordinator**

## Project Overview

StudySync is a responsive Blazor web application that helps college students find classmates, create course-specific study groups, and organize study sessions. Students often rely on scattered group messages or social media posts to coordinate academic collaboration. Important details such as the meeting time, location, subject, and available space can easily become difficult to find. StudySync will bring this information together in one organized application.

The primary users are university students who want to study collaboratively, especially students taking the same course but who may not already know one another. After signing in, a student will be able to browse groups, search by course or subject, create a group, schedule a session, and join or leave an upcoming session. A personal dashboard will summarize the user's groups and scheduled meetings.

The application is valuable because it addresses a practical student need while remaining achievable during the semester. It gives the team opportunities to demonstrate important .NET skills, including Razor components, authentication and authorization, database access with Entity Framework Core, input validation, responsive design, and collaborative development with GitHub and Trello.

## Project Scope

### In Scope

- Secure user registration, login, and logout.
- Basic student profiles containing a display name and optional academic interests.
- Creation, viewing, editing, and deletion of study groups by their owners.
- Course or subject information associated with each study group.
- Search and filtering by course, subject, and group name.
- Creation and management of scheduled study sessions.
- Join and leave functionality with session-capacity enforcement.
- A personal dashboard showing joined groups and upcoming sessions.
- Responsive layouts for desktop, tablet, and mobile browsers.
- Server-side validation and authorization for protected operations.

### Out of Scope

- A native Android or iOS application.
- Real-time chat, video conferencing, or screen sharing.
- Integration with university registration systems or Canvas.
- Automatic calendar synchronization.
- SMS, email, or push notifications.
- File uploads and permanent document storage.
- GPS tracking or turn-by-turn navigation.
- Paid subscriptions or payment processing.
- AI-generated study recommendations.

These exclusions keep the project focused on a reliable, well-tested minimum viable product. Additional capabilities can be considered only after all core requirements are complete.

## Core Features and User Stories

### 1. Account Registration and Authentication

Users can create an account, log in, and log out securely.

> As a student, I want to create an account and log in so that my groups and scheduled sessions are associated with me.

### 2. Student Profile

Users can view and update a basic profile containing their display name and academic interests.

> As a student, I want to maintain a simple profile so that other group members can identify me and understand what I am studying.

### 3. Study Group Management

Authenticated users can create study groups. Group owners can update or remove the groups they created.

> As a student, I want to create a study group for one of my courses so that classmates can discover and join it.

### 4. Browse, Search, and Filter

Users can browse available groups and search or filter them by course, subject, or group name.

> As a student, I want to search for groups by course so that I can quickly find relevant study opportunities.

### 5. Study Session Scheduling

Group owners can schedule sessions with a topic, date, start time, location, description, and participant capacity.

> As a group owner, I want to schedule a study session with clear details so that members know when and where to meet.

### 6. Join or Leave a Session

Authenticated users can join sessions with available space or leave sessions they can no longer attend.

> As a student, I want to join or leave a study session so that the participant list accurately reflects attendance plans.

### 7. Personal Dashboard

Users can see the groups they own or have joined and a chronological list of their upcoming sessions.

> As a student, I want one dashboard for my groups and upcoming sessions so that I can manage my study schedule efficiently.

## Technical Considerations

### Application Architecture

The application will use ASP.NET Core Blazor and C#. Razor components will provide the user interface, while services will contain business logic and isolate data-access operations. Entity Framework Core will manage relational data. The team will maintain the source code in GitHub and organize work with Trello.

### Data Storage

The initial relational model will include:

- `ApplicationUser`: authentication identity and profile information.
- `Course`: course code, title, and subject.
- `StudyGroup`: name, description, course, owner, and creation date.
- `GroupMembership`: relationship between users and study groups.
- `StudySession`: topic, date, time, location, capacity, and associated group.
- `SessionRegistration`: relationship between users and sessions.

SQLite is appropriate for local development and demonstrations. The data layer can later be configured for SQL Server if deployment requirements make that necessary.

### User Accounts and Authorization

ASP.NET Core Identity will provide account registration and authentication. Anonymous visitors may view public group information, but creating groups, joining sessions, or accessing a personal dashboard will require authentication. Only a group's owner will be authorized to edit or delete that group and manage its sessions.

### External Services

No external service is required for the minimum viable product. Avoiding external APIs reduces implementation risk and keeps the team focused on the required .NET concepts. Calendar, mapping, and notification integrations are possible future enhancements.

### Device Compatibility

The application will use responsive layouts and controls so it works in current desktop, tablet, and mobile browsers. The team will test common viewport sizes and ensure that primary workflows remain usable with both touch and pointer input.

### Basic Security

- Store passwords only through ASP.NET Core Identity's secure hashing mechanism.
- Require authentication for protected operations.
- Check resource ownership before editing or deleting records.
- Validate input on both the user interface and server.
- Use Entity Framework Core parameterization to reduce SQL-injection risk.
- Use HTTPS in development and deployment environments.
- Avoid storing unnecessary sensitive information.
- Protect forms and state-changing requests against cross-site request forgery where applicable.

## Project Links

- **GitHub Repository:** https://github.com/VictorChavez0501/CSE325-Group-Project
- **Trello Board:** https://trello.com/b/DHl8Xd43/cse-325-group-project

Both project resources must remain publicly accessible to the instructor. Every team member should be added to the GitHub repository as a collaborator and should have access to the Trello board.

## Initial Work Assignments

- **Victor Chavez:** Maintain the proposal and confirm repository access for all members.
- **Stephen Sanders:** Draft the initial data model and entity relationships.
- **Lucky Ayeni Inyang Eni:** Draft wireframes for group search and the personal dashboard.
- **Emmanuel Kalanda Owilli:** Research ASP.NET Core Identity setup and document the recommended approach.
- **All members:** Review the proposal, confirm the selected project, estimate the Trello feature cards, and choose tasks for the first development iteration.

## Submission Checklist

- [x] Meeting summary drafted.
- [x] Participant list included.
- [x] Project title and overview written.
- [x] In-scope and out-of-scope boundaries defined.
- [x] Seven core features written as user actions and user stories.
- [x] Data, authentication, compatibility, external services, and security considered.
- [x] GitHub and Trello links included.
- [x] StudySync confirmed as the project selected by the group.
- [ ] Confirm the next group leader.
- [ ] Add the seven feature cards and user stories to Trello.
- [ ] Verify that all members have GitHub collaborator access.
- [ ] Verify that GitHub and Trello are publicly accessible to the instructor.
