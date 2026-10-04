# DigiTales AI project overview

Open `dashboard.html`, or run the following from this directory:

```sh
python3 -m http.server 8931 --bind 127.0.0.1
```

Visit `http://127.0.0.1:8931/dashboard.html#overview`.

This is a read-only information page with two sections:

- **Overview:** project description, a six-stage roadmap, current position, and next checkpoint.
- **About the project:** purpose, supervisor and industry contact, member names / student IDs / emails, handbook essentials, and supplied references.

The roadmap is an indicative project sequence: Planning, Requirements, Design, Development, Testing, and Final showcase. Planning and scope is marked current based on the supplied meeting materials. It is not live progress tracking.

There is no backend, editable work plan, decision board, storage, or account system. The small JavaScript file only highlights the active navigation link. Native links and handbook disclosure elements work without it. The layout uses a fixed light palette with neutral surfaces and violet accents.

The original `index.html` remains the source project brief. Copies of the supplied documents remain under `sources/`. Tentative meeting dates and handbook targets are labelled; actual submission deadlines still need checking on Moodle. Filename examples in the handbook conflict, so verify the required convention before submitting.

Code and summaries were authored for Group 12 from user-supplied materials. Source documents remain attributed to their original authors.

## Project clarity and meeting records

The overview distinguishes established requirements from open scope questions. Meetings is a read-only archive, currently containing Meeting 01 and its original PDF. To add a record, copy the meeting article in `meetings.html`, update its date, attendance and summary, and place its minutes PDF under `sources/` with the corresponding link. No backend or browser storage is used.

Overview, About the project, and Meetings are separate static pages: `dashboard.html`, `about.html`, and `meetings.html`. Navigation uses ordinary page links.

The deployed homepage is `index.html`, which contains the current overview. `dashboard.html` remains a compatible copy for existing links. The original project brief is preserved as `project-brief.html`.
