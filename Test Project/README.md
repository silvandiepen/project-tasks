---
config: project
project: "Test Project"
lanes:
  - id: backlog
    name: Backlog
    folder: "0. Backlog"
    status: backlog
    backlog: true
  - id: to-do
    name: "To do"
    folder: "1. To do"
    status: to-do
  - id: in-progress
    name: "In Progress"
    folder: "2. In Progress"
    status: in-progress
  - id: in-review
    name: "In Review"
    folder: "3. In Review"
    status: in-review
  - id: testing
    name: Testing
    folder: "4. Testing"
    status: testing
  - id: done
    name: Done
    folder: "5. Done"
    status: done
    terminal: true
priorities:
  - id: P0
  - id: P1
  - id: P2
  - id: P3
users:
  - id: sil
    name: "Sil van Diepen"
    role: maintainer
  - id: alex
    name: "Alex Rivera"
    role: developer
  - id: jordan
    name: "Jordan Lee"
    role: developer
  - id: sam
    name: "Sam Okoro"
    role: designer
---

# Test Project


