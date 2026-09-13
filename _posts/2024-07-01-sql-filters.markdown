---
layout: case-study
modal-id: 7
title: SQL Security Filters
group: labs
icon: fa-filter
project-url: https://docs.google.com/document/d/1yhfq4oy0BZlPIZ6KnM_ikucEN-_l-HDY1Zg5oa2vYKs/view?usp=sharing
description: Used SQL filters to investigate after-hours failed logins and evaluate records by date, location, and department.
scenario: A security team needed to investigate authentication records for suspicious failed-login activity and narrow the review to relevant people, times, and locations.
objective: Use SQL filtering to isolate log events that warrant closer security analysis.
tools:
  - SQL WHERE clauses
  - Logical operators
  - Authentication-log dataset
tasks:
  - Retrieved failed login attempts that occurred outside normal business hours.
  - Filtered login attempts by date and geographic location.
  - Queried employee records by department to support targeted review.
findings-label: Skills demonstrated
findings:
  - title: Focused investigation
    detail: Filters reduce a large dataset to the events most relevant to a specific security question.
  - title: Logical conditions
    detail: AND, OR, and NOT operators make it possible to express multi-part investigation criteria precisely.
  - title: Repeatable analysis
    detail: Saved query patterns can support consistent triage when similar authentication questions arise.
recommendations-label: Next step
recommendations:
  - Pair filtered query results with contextual data before treating an event as malicious.
  - Document useful query patterns so they can be reused during future investigations.
  - Continue practicing SQL against larger security-log datasets.
---
