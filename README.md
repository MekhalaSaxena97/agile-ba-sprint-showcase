What this project is

Most portfolios show code. This one shows what comes before the code.
This repository contains the complete set of Business Analyst artifacts produced for a fictional but realistic Agile sprint at NedBank Digital — a Dutch mobile-first bank. The feature: redesigning a broken customer document upload journey that had a 32% drop-off rate and was costing the business an estimated €2.1M in annual revenue.
The goal is simple: demonstrate what a senior BA actually produces in a 2-week sprint — from stakeholder analysis to signed-off user stories — and make that work visible.

The business problem:

One in three customers who began the identity verification process abandoned it.
The cause was not a system failure. It was a design and ownership failure.

MetricCurrent stateUpload drop-off rate32%Estimated annual revenue at risk€2.1MSupport tickets per month (upload-related)1,840Average verification completion time4.2 daysRoot causeNo product owner assigned post-2023 restructure

The 6 BA artifacts
#ArtifactDescriptionStatus1Business Problem StatementSituation, root cause (5 Whys), business impact across 3 levers, success metrics✅ Complete2Stakeholder RegisterPower/interest matrix, RACI, 6 stakeholders with engagement strategy✅ Complete3AS-IS Process MapBPMN 2.0 swimlane diagram — 3 lanes, 6 annotated failure points🔄 In progress4User Stories + Acceptance Criteria10 stories, Given/When/Then AC, MoSCoW prioritisation✅ Complete5Jira Sprint BoardSprint setup, epics, story points, capacity planning🔄 In progress6TO-BE Process MapBPMN 2.0 future-state diagram with improvement annotations🔄 In progress

Skills demonstrated
Business Analysis          Requirements Engineering    Agile / Scrum
─────────────────────────  ──────────────────────────  ─────────────────────
✦ Business problem framing  ✦ User story writing         ✦ Sprint planning
✦ Stakeholder mapping       ✦ Acceptance criteria        ✦ Backlog refinement
✦ Root cause analysis       ✦ MoSCoW prioritisation      ✦ Jira board setup
✦ Gap analysis              ✦ Requirements traceability  ✦ Velocity estimation
✦ Business case writing     ✦ Non-functional req.        ✦ DoD and DoR

Process Modelling          Documentation
─────────────────────────  ──────────────────────────
✦ BPMN 2.0 notation        ✦ Professional BA documents
✦ Swimlane diagrams         ✦ Confluence page structure
✦ AS-IS / TO-BE mapping    ✦ Data-driven business cases
✦ Failure point analysis

Repository structure
agile-ba-sprint-showcase/
│
├── 01-business-problem-statement/
│   └── business-problem-statement-v1.pdf
│
├── 02-stakeholder-register/
│   └── stakeholder-register-v1.pdf
│
├── 03-asis-process-map/
│   ├── asis-document-upload-v1.drawio      ← editable source
│   └── asis-document-upload-v1.png         ← exported visual
│
├── 04-user-stories/
│   └── user-stories-acceptance-criteria-v1.pdf
│
├── 05-jira-board/
│   └── sprint-board-screenshot.png
│
├── 06-tobe-process-map/
│   ├── tobe-document-upload-v1.drawio
│   └── tobe-document-upload-v1.png
│
└── README.md

Process maps — AS-IS vs TO-BE

Diagrams coming in the next update. Preview below.

AS-IS (current state) — 3 swimlanes, 6 failure points identified
[BPMN diagram — uploading shortly]
TO-BE (future state) — same lanes, failure points eliminated
[BPMN diagram — uploading shortly]

The methodology
This project follows Agile BA practice — the way a BA actually works inside a Scrum team, not the waterfall version taught in textbooks.
Each artifact maps to a real sprint event:

Business Problem Statement → written before Sprint 0 to justify the work
Stakeholder Register → completed in the discovery phase, before a single user story is written
AS-IS Process Map → produced through stakeholder interviews and process observation
User Stories + AC → written in Backlog Refinement, sprint-ready for Sprint 1
Jira Board → the sprint loaded with Must-Have stories, story-pointed, and ready to go
TO-BE Process Map → the target state that guides Sprint 1 delivery and UAT planning
