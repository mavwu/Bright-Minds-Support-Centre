# Bright Minds Support Centre: implementation guide

A parent-facing tutoring website presenting Maths, ICT, and Computer Studies support, lesson information, schedules, and enrolment contact options.

## Scope

**Repository role:** Service website.

The website communicates services and hands off enquiries. It has no student records, enrolment database, or online lesson-management backend.

## Local evaluation

Run a static server from the repository root:

```sh
python -m http.server 4173
```

Open `http://localhost:4173` and select the relevant HTML page or variant directory. No build step is required for plain HTML/CSS/JavaScript. Use a server when scripts fetch local content; opening a file directly can produce different behavior.

## Code map

| Path | Responsibility |
| --- | --- |
| `index.html` | Page or browser application entry |
| `style.css` | Presentation and responsive styles |

## Walkthrough

Find a subject, understand the lesson process and pricing, and reach the enrolment contact path from a narrow screen.

## Verification

No meaningful automated application check was established from the reviewed manifest. Evaluate the walkthrough with synthetic data and record the commit, environment, and result. For a static site, inspect narrow/wide layouts, keyboard focus, links, forms, and console errors.

## Evidence for a case study

Describe this repository as a **service website**. A useful case study explains the problem above, traces the walkthrough to its source, names a concrete implementation decision, and records a repeatable evaluation. Separate implemented behavior from roadmap work. Capture screenshots using synthetic data and identify the demonstrated commit.
