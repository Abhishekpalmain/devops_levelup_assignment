# Student Attendance Management System

A small browser-based project for managing a class attendance list. It uses local browser storage, so no server or account on a website is needed for the demo.

## Run

Open `index.html` in a current browser. Add a student, choose a date, and mark attendance.

## First version

- Add students
- Mark a student present or absent for a selected date
- Update an existing record for the same student and date instead of duplicating it
- View selected-date totals
- Persist data in this browser using localStorage

## GitHub Actions

The `Student Attendance CI` workflow runs on pushes and pull requests to `main` or `master`, and can also be started manually. It checks that the main project files are present. The workflow is in `.github/workflows/ci.yml`.

## Jira board

Use the issues in [KANBAN.md](KANBAN.md) as Jira cards. Create a Jira Kanban board with To Do, In Progress, and Done columns, then move the cards as you work.

## Limitations

This is a learning/demo app. Data stays in the current browser and is not backed up to a server. It has no login, roles, or multi-device synchronization.
