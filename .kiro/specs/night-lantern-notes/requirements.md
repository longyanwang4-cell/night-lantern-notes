# Requirements: Night Lantern Notes

## Introduction

A single-page, offline-first notebook for Kiroween 2026, Costume Contest.
Dark lantern visual theme, but the function is a serious notebook.

## Requirements

### Requirement 1: Create a note
**User Story:** As a user, I want to add a note, so that I can record something at night without an account.
#### Acceptance Criteria
1. WHEN the user enters a title and/or body and clicks add, THEN the note appears at the top of the list with a creation timestamp.
2. WHEN both fields are empty, THEN the app refuses to add and shows a prompt.

### Requirement 2: Persist locally
**User Story:** As a user, I want my notes to survive a page reload, so that I do not lose field notes.
#### Acceptance Criteria
1. WHEN the page reloads, THEN previously added notes are still listed.
2. WHEN there is no network, THEN adding, listing, searching and deleting still work.

### Requirement 3: Search and delete
**User Story:** As a user, I want to search and delete notes, so that I can manage the list.
#### Acceptance Criteria
1. WHEN the user types in search, THEN only matching notes are shown.
2. WHEN the user deletes a note, THEN it disappears and stays deleted after reload.

### Requirement 4: Export CSV
**User Story:** As a user, I want to export notes as CSV, so that I can organise them later in a spreadsheet.
#### Acceptance Criteria
1. WHEN the user clicks export, THEN a CSV file downloads containing createdAt, title and body for every note.
2. WHEN a field contains commas or quotes, THEN the CSV escaping keeps the file valid.

### Requirement 5: No backend, no copyrighted material
**User Story:** As a submitter, I want zero backend and zero third-party assets, so that GitHub Pages hosting and the demo video stay clean.
#### Acceptance Criteria
1. WHEN the app loads, THEN it needs no server API and no external font, image or music file.
2. WHEN the app is opened from a static host, THEN all features work.
