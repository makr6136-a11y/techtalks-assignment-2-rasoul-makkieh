# 5. Portfolio Plan

## Approach

Three projects of deliberately unequal size, not three equal ones. The reasoning is the hour budget set out in [`roadmap.md`](roadmap.md): roughly 240 hours over six months is enough to build one thing properly or three things badly. Projects 1 and 2 are small, produced inside month 2 while learning REST APIs, and exist to prove specific skills. Project 3 is the flagship, carried from month 4 through month 6 rather than restarted, and it is the one an employer would actually open.

Each project is mapped to the frequency counts in [`market-research.md`](market-research.md). Nothing is included because it is popular; every skill listed below appears in at least 2 of the 6 listings analyzed.

## Project 1 — Course Planner API (Month 2, small)

**What it is:** A CRUD REST API for managing university courses, instructors, schedules and student enrollments using a relational database.

**Skills it proves:**

| Skill | Evidence |
|---|---|
| REST APIs | 6 / 6 — highest-scoring requirement in the sample |
| Relational databases / SQL | 6 / 6 |
| Documentation | 4 / 6 — listings 1, 3, 5, 6 |
| Git | 4 / 6 — listings 2, 3, 4, 6 |

**Which listings asked for this:** all six require REST APIs and SQL. Listing 2 (Presentail, the intern role I can apply to today) asks specifically for "server-side logic and databases" and "basic understanding of client-server architecture, APIs and databases."

**Done when:** the API supports full CRUD with correct HTTP verbs and status codes, runs against a real database rather than an in-memory array, and has endpoint documentation written in English.

## Project 2 — Developer Job Tracker (Month 2, small)

**What it is:** A JavaScript web application that retrieves developer jobs from a third-party API and lets users search and filter them by role, location and required skills.

**Skills it proves:**

| Skill | Evidence |
|---|---|
| Third-party API integration | Listings 1, 3, 6 |
| JavaScript (ES6+) | 4 / 6 — listing 2 specifies ES6+ |
| HTML / CSS | 4 / 6 |

**Which listings asked for this:** listing 1 requires "REST APIs and integrations with platforms including Zoom, Google Workspace, Microsoft Teams"; listing 3 requires building "CRM, email, analytics, payment, notification and third-party integrations." Consuming somebody else's API is a distinct skill from building your own, and both appear in the sample.

**Done when:** the app handles the failure cases as well as the success case — network error, rate limit, empty result — because that is the difference between a tutorial and something that works.

## Project 3 — Appointment Booking Platform (Months 4–6, flagship)

**What it is:** A server-rendered PHP application where customers create accounts and book appointments while staff manage schedules, availability and bookings through a role-protected dashboard.

**Skills it proves:**

| Skill | Evidence |
|---|---|
| PHP, server-side fundamentals | 2 / 6 — listings 1 and 2, both local |
| Authentication and security | 3 / 6 |
| Schema design | Listings 1 and 4 ask for design, not just querying |
| REST APIs | 6 / 6 |
| Documentation | 4 / 6 |
| Deployment | Listing 4 requires deployment workflows; listings 5 and 6 require AWS |

**Which listings asked for this:** listing 2 asks for PHP, JavaScript, HTML, CSS, Git, APIs and databases — this project covers every one of them. Listing 5 expects even a "junior" hire to remediate vulnerabilities and patch dependencies, while listings 3 and 4 also require authentication, permissions or secure application design.

**Done when:** it is live at a URL a stranger can visit, has registration with hashed passwords, sessions and role-based access, sits in a public repo with a readable commit history, and has a README that explains what it does and why the schema looks the way it does.

## What these projects do not prove

Being explicit about the gaps is more useful than pretending there aren't any.

- **No CI/CD, cloud, Docker or Infrastructure as Code.** Their required counts are 2/6, 3/6, 1/6 and 1/6 respectively, with CI/CD also preferred in listing 6. They are deliberately out of scope until after a first job, per the roadmap.
- **No React, Next.js or TypeScript.** Each scores 1/6 and appears in listing 4. Deferred, not dropped.
- **No automated testing.** Jasmine/Karma and Pytest are required in listing 6; Jest, Cypress and TDD are preferred in listing 4. Manual testing and debugging (listings 2, 3) are covered, but an experienced employer would see this gap.
- **No NoSQL.** It appears in 2/6, alongside relational database options rather than replacing them.

Taken together, these projects are aimed at the local entry point identified in the research. They would not make me competitive for listings 4, 5 or 6 — and nothing achievable in six months would.
