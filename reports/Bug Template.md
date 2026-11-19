Bug Report Template
Copy this file for each bug. Name it `BUG-001.md`, `BUG-002.md`, and so on. Keep screenshots and videos in an `evidence/` folder and link them below.
---
BUG-001: [Area] Short, specific summary of the problem
Field	Value
Date reported	YYYY-MM-DD
Reporter	Your name
Application / URL	
Version / Build	
OS	
Browser / Device	
Test account / data used	
Type	Functional / UI / Usability / Performance / Compatibility
Severity	Critical / Major / Minor / Trivial
Priority	High / Medium / Low
Reproducibility	Always / Intermittent (e.g. 3 of 5 attempts)
Preconditions
What must be true before starting (logged in, cart has 2 items, and so on).
Steps to Reproduce



Expected Result
What should happen, ideally with a reason (spec, UI text, standard behaviour).
Actual Result
What actually happens. Facts only, no opinions.
Evidence
Screenshot: `evidence/BUG-001-screenshot.png`
Video: `evidence/BUG-001-video.mp4`
Notes / Workaround
Anything that helps the developer: workaround, related bugs, when it started.
---
Quick Guide
Title formula: `[Area] What breaks + under what condition`
Good: `[Checkout] Total does not update after removing an item`
Weak: `Checkout is broken`
Severity (how bad is the impact?)
Critical: crash, data loss, or a core flow is completely blocked
Major: a main feature fails, but a workaround exists
Minor: a small functional or UI issue that does not block the user
Trivial: cosmetic (typo, 1px misalignment)
Priority (how soon should it be fixed?) is the business call. A typo on the homepage can be low severity but high priority.
Rules
One bug per report.
Steps must be repeatable by a stranger with no extra explanation.
Retry before reporting, so you can fill in Reproducibility honestly.
Describe what you saw, not who is to blame.
Always attach evidence.
