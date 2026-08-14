# 4. Six-Month Learning Roadmap

*Assumptions, stated so they can be challenged: (1) the near-term target is the local market, because listing 2 is the only role in the sample I could apply to today; (2) success at month 6 means internship-ready with one deployed project as evidence; (3) the hour budget is a flat 10 hours per week, held constant rather than assumed to rise over the break. Prior coursework completed: OOP I (Java), Web Design (HTML/CSS), Database Design (basic SQL).*

## Strategy

**Foundation-first, with a local tilt from month 4.**

The frequency table makes the case on its own: REST APIs and SQL each scored 6/6, while no framework exceeded 2/6 — not React, not Vue, not Next.js, not Laravel. Spending the first three months on a framework would be optimizing for a 2-in-6 chance while leaving the two universal requirements unmet. The fundamentals are also the only portable part of the plan: REST, SQL, JavaScript, Git and auth appear across both markets, so months 1–3 stay valuable no matter which way the stack decision goes.

The stack decision itself is settled by seniority, not preference. The remote group (listings 4, 5, 6) has no genuine entry point — 5+ years, four years behind a "Junior" title, and Lead I — and layers CI/CD, cloud and Infrastructure as Code on top. Six months does not close that gap, and pretending otherwise would make this roadmap fiction. The local group contains the one reachable role in the sample: listing 2, an intern position asking for basic-to-intermediate PHP, JavaScript, HTML, CSS, Git, APIs and databases. That listing is effectively the specification for months 1–6, and I already hold two of its requirements outright.

So the sequence is: shared foundation first (months 1–3), local stack second (months 4–5), shipped evidence third (month 6). Infrastructure — the CI/CD, cloud and IaC cluster that appears in every remote listing and almost no local one — is deliberately out of scope here. It is the bridge from the local market to the remote one, and it is the right investment for months 7–18, once there is a job to build it on top of.

One correction to my own default: Next.js, which I currently have in progress, serves the remote market that will not hire at my level for two more years, and appears in 1 of 6 listings. Continuing it by inertia would be spending scarce hours on the lowest-scoring row in the table. It is deferred below, not abandoned.

## Constraints

**10 hours per week, flat.** That is roughly 40 hours per month and 240 hours in total — the entire budget for this roadmap. It is enough, but only because four university courses carry part of the load. Anything outside the monthly focus gets cut, not squeezed in.

| | Hours |
|---|---|
| Per week | 10 |
| Per month | ~40 |
| Six-month total | ~240 |

Four courses overlap this plan and are treated as free hours rather than competing ones:

* **Web Programming I** — overlaps months 1 and 4 (client-side and server-side web fundamentals). The largest single saving in the plan.
* **Database Programming** — overlaps month 3 almost entirely; the schema-design depth listings 1, 4 and 6 ask for is coursework, not extra study.
* **OOP II** — reinforces concepts that transfer, though Java itself scored 0/6. Coursework only; no Java outside class.
* **Software Design** — supports the architecture and documentation expectations in listings 1 and 3.

**What 10 hours buys, honestly.** Forty hours is enough to learn one thing properly or two things badly. Each month therefore has a single focus and a single deliverable, and the flagship project is carried forward from month 4 to month 6 rather than restarted — building three separate applications at this budget would produce three shallow ones. The tightest month is 2 (REST APIs from zero); the most protected is 3, where coursework does most of the work. If a month slips, month 6 absorbs it and the applications go out later — the sequence does not get reordered to catch up.

## Month-by-month

| Month | Focus | Why (evidence) | Done when |
|-------|-------|----------------|-----------|
| 1 | JavaScript (ES6+) and Git | JavaScript is 4/6 and named explicitly in listing 2 as "ES6+". Git is 3/6 as stated but closer to 6/6 in practice — listings 5 and 6 both require CI/CD pipelines, which cannot function without version control, yet name no VCS. Also the fastest way to convert existing HTML/CSS into something interactive | I can write ES6 (fetch, promises/async, destructuring, modules) without a tutorial open, and have a repo with a branch-and-merge history rather than a single main branch |
| 2 | REST APIs — consume, then build | The highest-scoring row in the entire table, 6/6, present in every listing including the intern role. Listing 1 and 3 both add third-party integration on top | I have built a CRUD API with proper verbs and status codes, consumed a third-party API in a small app, and written endpoint documentation for both |
| 3 | SQL depth and schema design | 6/6, and listings 1, 4 and 6 ask for schema design and query optimization specifically — not just querying. My current SQL is basic, so this is upgrading a held skill rather than starting one. Overlaps Database Programming almost entirely | I have designed a normalized multi-table schema from a written brief, and can explain an index choice and a slow-query fix out loud |
| 4 | PHP server-side fundamentals | PHP appears in 2/6 — listings 1 and 2 — and both are local and on-site. Listing 2 asks for basic-to-intermediate PHP, client-server architecture and server-side logic, which is exactly this month. Zero remote listings use PHP, which is why this is month 4 and not month 1 | I have built a server-rendered app with routing, form handling, session state and a database layer, without a framework |
| 5 | Authentication and security | 4/6, and required even of the role labelled Junior — listing 5 expects vulnerability remediation and dependency patching, listing 6 names injection and broken object-level authorization, listing 3 names permissions and data privacy. It is the requirement least likely to be forgiven in an interview | My month-4 app has registration, hashed passwords, sessions and role-based access, and I can explain SQL injection, XSS and BOLA with the fix for each |
| 6 | Deploy, document, apply | Documentation appears in 3/6 (runbooks and SOPs in 1, technical and release docs in 3, root-cause write-ups in 5) and some non-technical requirement — English, communication, documentation, code review — appears in 5 of 6, more than any single framework. Listing 1 names written English outright. A project nobody can visit is not evidence | The project is live at a URL, has a README and API documentation written in English, sits in a public repo with a readable commit history, and I have submitted applications to intern and junior local roles |

## What I am deliberately not learning

**Java and Spring — 0/6.** Not one of the six listings mentions either, despite Java being a standard track and my strongest current language. OOP II continues as coursework because the concepts transfer and the credit is required, but no hour outside class goes to Java. This is the single largest gap between what I already have and what this market pays for.

**C++ — 0/6.** Does not appear anywhere in the sample, not even as a nice-to-have.

**Next.js and React — 1/6 and 2/6, remote-only.** Both appear exclusively in listings 4 and 6, which are remote roles requiring five years and Lead-level experience respectively. Deferred to months 7+, after a local role, rather than dropped — the JavaScript work in month 1 is the prerequisite either way, so nothing is wasted.

**TypeScript — 1/6.** Listing 4 alone. Worth adding once JavaScript is solid; worthless before then.

**GraphQL — 2/6.** Listings 4 and 6 only, and both ask for it *alongside* REST rather than instead of it. REST is the requirement; GraphQL is the extra.

**CI/CD, cloud, Docker and Infrastructure as Code — 3/6, 3/6, 2/6, 2/6.** The strongest pattern in the research: CI/CD and IaC appear only in remote listings, and cloud and Docker appear in local listings only twice (listing 3's cloud deployment, listing 1's Docker). This is the skill cluster that converts a local profile into a remote one — which is exactly why it belongs after a first job, not before one.

**NoSQL — 2/6.** Listings 4 and 6, both remote, and both alongside a relational database rather than replacing it. Relational SQL is 6/6 and is where the month-3 hours go.

**Vue — 1/6.** Listing 1 only, and that role wants five years. If a local employer asks for Vue, the JavaScript foundation from month 1 makes it a short jump.

**Testing frameworks — nice-to-have only.** Jest, Cypress and TDD appear as *preferred* in listing 4 and as a requirement nowhere. Basic debugging and manual testing (listings 2 and 3) are covered inside the monthly projects.

**AI and LLM integration — 1/6.** A hard requirement in listing 3 only, plus two excluded listings per `sources.md`. Three sightings in a wider pool is worth watching, not worth six months of a beginner's time. Revisit at month 6.