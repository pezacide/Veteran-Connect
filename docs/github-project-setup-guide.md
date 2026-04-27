# Veteran Connect GitHub Project setup guide

This guide is written for a beginner and assumes the repository already exists at `pezacide/Veteran-Connect`.

## What has already been done
The repository has been initialized.
A project history and backlog document has been added.
A CSV issue seed has been added.
Some historical record issues have already been created so there is real content to start from.

## Goal
Create one GitHub Project that shows:
- what has already been completed
- what is in progress now
- what still needs to be done
- which stream each item belongs to
- which items are highest priority

## Part 1: Open the repository
1. Sign in to GitHub.
2. Open `pezacide/Veteran-Connect`.
3. Keep this repository open in one tab.

## Part 2: Create the project board
1. In GitHub, click the profile picture in the top right.
2. Click **Your projects**.
3. Click **New project**.
4. Choose **Board**.
5. Name it `Veteran Connect Build Tracker`.
6. Click **Create**.

## Part 3: Create the custom fields
Create these fields one by one.

### Status
Type: Single select
Options:
- Done
- In Progress
- Open
- Blocked

### Stream
Type: Single select
Options:
- Android
- Web
- MAUI
- iOS
- Backend
- Auth
- Security
- AI
- Provider Services
- Docs
- Ops
- QA
- GitHub
- Cross-platform

### Platform
Type: Single select
Options:
- Android
- Web
- MAUI
- iOS
- Shared Swift
- Backend
- Cross-platform
- GitHub
- Docs
- QA

### Priority
Type: Single select
Options:
- Critical
- High
- Medium
- Low

### Type
Type: Single select
Options:
- Epic
- Task
- Bug
- Historical record
- Planning

### Confirmed Date
Type: Date

## Part 4: Link the project to the repo
1. In the project, open **Settings**.
2. Find the repository connection area.
3. Add `pezacide/Veteran-Connect` as a linked repository.
4. Turn on automatic item adding for issues if GitHub offers that option.

## Part 5: Import the existing issues
If the issues already exist in the repository, add them to the project.

1. In the project, click **Add item**.
2. Search for issues from `pezacide/Veteran-Connect`.
3. Add the seeded issues.
4. Start with the historical records and current work items first.

## Part 6: Fill the fields for each issue
Use this pattern:

- Historical record issues:
  - Status = Done
  - Type = Historical record
- Active work issues:
  - Status = In Progress or Open
  - Type = Task or Epic
- Priority:
  - Use Critical for platform-shaping work
  - Use High for active delivery work
  - Use Medium for cleanup and follow-on work

## Part 7: Create the main views
### View 1: Roadmap
Show all items grouped by Status or Stream.

### View 2: Current Build Focus
Filter:
- Status is Open or In Progress
- Priority is Critical or High

### View 3: MAUI Build
Filter Stream = MAUI

### View 4: Web Claim Pack
Filter Stream = Web

### View 5: Security and Auth
Filter Stream = Auth, Security, Cross-platform

### View 6: Done History
Filter Status = Done

## Part 8: Use the repo files as your source of truth
Use these files when you need to remember what belongs in the tracker:
- `docs/project-history-backlog.md`
- `project-management/github-issue-seed.csv`

## Part 9: Suggested order for the next issues
After the existing seeded history items, create or import these next:
1. Create Veteran Connect GitHub Project structure
2. Build Provider Services as a first-class Veteran Connect module
3. Rebuild dashboard work safely on top of the restored MAUI baseline
4. Fix login/dashboard navigation and preserve new brand styling
5. Finish Physicians Initial Liability responsive layout cleanup
6. Align web Claim Starter Pack with DVA portal-style structure
7. Implement unified account management across platforms
8. Implement security and privacy baseline controls
9. Build native iPhone app shell using shared Swift core
10. Create consolidated architecture and setup documentation

## Part 10: What good looks like
A good first version of the project should let someone open the board and immediately understand:
- what has already been delivered
- what is being actively worked on now
- what the next major epics are
- which platform each item belongs to

## Part 11: Keep it simple at the start
Do not try to create every possible field, automation, or workflow on day one.
Start with the fields above.
Add the main issues.
Group work by stream.
Then improve it later.
