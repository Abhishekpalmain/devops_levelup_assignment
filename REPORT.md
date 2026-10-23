# Project Report: Student Attendance Management System

## Objective

Create a simple system for maintaining a student list and recording whether each student is present or absent on a selected date. Track the work using a Kanban board with To Do, In Progress, and Done columns.

## Requirements

- Add students to a class list.
- Select an attendance date.
- Mark each student Present or Absent.
- Show attendance totals and students not yet marked.
- Keep one attendance record per student per date; changing the status updates the existing record.
- Show the project work on a Kanban board.

## Tools and implementation

The first version is a single-page HTML, CSS, and JavaScript application. It stores students and attendance records in the browser's localStorage, so data persists in that browser on that device. The Kanban work plan is documented in `KANBAN.md`.

## Implemented feature: Mark Attendance

The user selects a date and presses Present or Absent beside a student. The app saves the student's ID, selected date, and status, then refreshes the row and totals. If a record already exists for that student and date, the app changes its status instead of adding another record.

## Evidence to add after hands-on verification

1. Screenshot of the Kanban board showing the task columns and current cards.
2. Screenshot of the attendance page with at least one student and a marked status.
3. Optional screenshot showing a refreshed page with the saved status still visible.

## Demonstration steps

1. Open `index.html` in a browser.
2. Add a student using the Add a student form.
3. Leave today's date selected, then click Present for that student.
4. Show the Present count and the student's status.
5. Refresh the page and show that the status remains.
6. Click Absent for the same student and date to demonstrate that the existing entry is updated.

## Limitations and next work

This is a local learning prototype. It has no user login, server database, multi-user access, cloud backup, or attendance export yet. Before submission, complete the demonstration steps, capture the evidence screenshots, and update the Kanban board to reflect the verified state.
