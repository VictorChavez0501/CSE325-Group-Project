# Contributing to StudySync

## Initial Setup

1. Clone the repository.
2. Install the .NET 9 SDK.
3. Restore and build the project:

```powershell
dotnet restore CSE325GroupProject/CSE325GroupProject.csproj
dotnet build CSE325GroupProject/CSE325GroupProject.csproj
```

4. Run the application:

```powershell
dotnet run --project CSE325GroupProject/CSE325GroupProject.csproj
```

## Branch Workflow

Create one branch for each Trello task. Use a short, descriptive name with one of these prefixes:

- `feature/` for new user-facing functionality.
- `task/` for supporting development work.
- `fix/` for defects.
- `docs/` for documentation-only work.

Examples:

```text
feature/study-group-model
task/identity-plan
docs/dashboard-wireframes
```

## Before Opening a Pull Request

- Confirm that the work satisfies the Trello card's acceptance criteria.
- Run `dotnet build` and resolve all errors and warnings introduced by the change.
- Review the changed files and remove unrelated edits.
- Use clear commit messages describing the completed work.
- Link the Trello card in the pull-request description.
- Add testing or manual-verification notes.

## Review and Merge

- Request review from at least one teammate for meaningful code changes.
- Respond constructively to review comments.
- Do not merge work that fails to build.
- After merging, move the Trello card to Done and delete the completed branch when appropriate.

