# 5. Portfolio Plan

## Approach

Three projects of deliberately unequal size, not three equal ones. The reasoning is the hour budget set out in [`roadmap.md`](roadmap.md): roughly 240 hours over six months is enough to build one thing properly or three things badly. Projects 1 and 2 are small, produced inside month 2 while learning REST APIs, and exist to prove specific skills. Project 3 is the flagship, carried from month 4 through month 6 rather than restarted, and it is the one an employer would actually open.

Each project is mapped to the frequency counts in [`market-research.md`](market-research.md). Nothing is included because it is popular; every skill listed below appears in at least 2 of the 6 listings analyzed.

## Project 1 — <name> (Month 2, small)

**What it is:** `TODO — a CRUD API over a small domain of your choice. Pick something you understand well enough to model without research.`

**Skills it proves:**

| Skill | Evidence |
|---|---|
| REST APIs | 6 / 6 — highest-scoring requirement in the sample |
| Relational databases / SQL | 6 / 6 |
| Documentation | 3 / 6 — listings 1, 3, 5 |
| Git | 3 / 6 stated, 5–6 / 6 in practice |

**Which listings asked for this:** all six require REST APIs and SQL. Listing 2 (Presentail, the intern role I can apply to today) asks specifically for "server-side logic and databases" and "basic understanding of client-server architecture, APIs and databases."

**Done when:** the API supports full CRUD with correct HTTP verbs and status codes, runs against a real database rather than an in-memory array, and has endpoint documentation written in English.

## Project 2 — <name> (Month 2, small)

**What it is:** `TODO — a small app that consumes a third-party API and does something useful with the response.`

**Skills it proves:**

| Skill | Evidence |
|---|---|
| Third-party API integration | Listings 1, 3, 6 |
| JavaScript (ES6+) | 4 / 6 — listing 2 specifies ES6+ |
| HTML / CSS | 4 / 6 |

**Which listings asked for this:** listing 1 requires "REST APIs and integrations with platforms including Zoom, Google Workspace, Microsoft Teams"; listing 3 requires building "CRM, email, analytics, payment, notification and third-party integrations." Consuming somebody else's API is a distinct skill from building your own, and both appear in the sample.

**Done when:** the app handles the failure cases as well as the success case — network error, rate limit, empty result — because that is the difference between a tutorial and something that works.

## Project 3 — <name> (Months 4–6, flagship)

**What it is:** `TODO — a server-rendered PHP application with real users, real data and real permissions. It needs more than one kind of user so that authorization is genuine rather than decorative.`

**Skills it proves:**

| Skill | Evidence |
|---|---|
| PHP, server-side fundamentals | 2 / 6 — listings 1 and 2, both local |
| Authentication and security | 4 / 6 |
| Schema design | Listings 1, 4, 6 ask for design, not just querying |
| REST APIs | 6 / 6 |
| Documentation | 3 / 6 |
| Deployment | Listing 4 requires deployment workflows; listings 5 and 6 require AWS |

**Which listings asked for this:** listing 2 asks for PHP, JavaScript, HTML, CSS, Git, APIs and databases — this project covers every one of them. Listing 5 expects even a "junior" hire to remediate vulnerabilities and patch dependencies; listing 6 names injection and broken object-level authorization explicitly.

**Done when:** it is live at a URL a stranger can visit, has registration with hashed passwords, sessions and role-based access, sits in a public repo with a readable commit history, and has a README that explains what it does and why the schema looks the way it does.

## What these projects do not prove

Being explicit about the gaps is more useful than pretending there aren't any.

- **No CI/CD, cloud, Docker or Infrastructure as Code.** These appear in every remote listing (CI/CD 3/6, cloud 3/6, IaC 2/6) and are deliberately out of scope until after a first job, per the roadmap. A remote employer would see this gap immediately. A local employer, based on listings 1, 2 and 3, mostly would not.
- **No React, Next.js or TypeScript.** Scoring 2/6, 1/6 and 1/6 respectively, and remote-only. Deferred, not dropped.
- **No automated testing.** Jest, Cypress and TDD appear as *preferred* in listing 4 and as a requirement in none. Manual testing and debugging (listings 2, 3) are covered inside each project.
- **No NoSQL.** 2/6, both remote, both alongside a relational database rather than replacing it.

Taken together, these projects are aimed at the local entry point identified in the research. They would not make me competitive for listings 4, 5 or 6 — and nothing achievable in six months would.
