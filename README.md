# Lab Agile Planning

A lightweight agile planning repository designed to support collaborative backlog creation, user story definition, and acceptance criteria tracking in a practical lab environment.

## Overview

This repository serves as a working template for agile planning exercises. It is intended to help teams and learners practice the fundamentals of agile delivery by defining user stories, clarifying requirements, and shaping work into measurable outcomes.

Instead of focusing on an application implementation, this project emphasizes the planning side of software delivery: understanding user needs, writing clear stories, and validating them through well-defined acceptance criteria.

## Objectives

- Capture user needs in a structured, consistent format
- Promote shared understanding across stakeholders and delivery teams
- Encourage clear acceptance criteria and testable outcomes
- Support iterative planning and backlog refinement
- Provide a reusable lab environment for agile learning and workshops

## Repository Structure

```text
.
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── user-story.md
├── README.md
└── .gitignore
```

### Key artifact

- `.github/ISSUE_TEMPLATE/user-story.md` — a reusable template for creating user stories with:
  - role
  - need
  - benefit
  - assumptions and details
  - acceptance criteria in Gherkin format

## Agile Workflow

This repository follows a simple agile planning flow:

1. Define a user need
2. Write a user story using the standard format
3. Capture assumptions and constraints
4. Add acceptance criteria
5. Review with stakeholders
6. Prioritize and implement in future iterations

### User Story Format

The standard pattern used in this lab is:

```text
As a [role]
I need [function]
So that [benefit]
```

This format keeps the work customer-focused and ensures the business value is always explicit.

## Creating a User Story

Use the issue template located at `.github/ISSUE_TEMPLATE/user-story.md` to create a structured story. Each story should include:

- the actor or role
- the capability required
- the value delivered
- relevant assumptions or constraints
- acceptance criteria expressed as testable scenarios

### Example

```gherkin
Given a logged-in user
When they open the dashboard
Then they should see their upcoming tasks and priorities
```

## Getting Started

1. Open the repository in GitHub.
2. Create a new issue using the User Story template.
3. Complete the fields for role, need, benefit, details, and acceptance criteria.
4. Review the story with your team or workshop participants.
5. Use the result as a backlog item or discussion starter for planning.

## Why This Repository Exists

This repository is intended for learning and practice, especially in environments where teams want to strengthen:

- backlog refinement
- story writing
- prioritization conversations
- user-centered product thinking
- acceptance criteria validation

## Contributing

Contributions are welcome when they improve the planning workflow, refine the template, or enhance the learning experience.

Recommended approach:

- create a branch for your changes
- update the template or documentation as needed
- validate that the content remains clear and practical
- open a pull request for review

## Best Practices

- Keep user stories specific, measurable, and user-centered
- Write acceptance criteria in a way that can be tested
- Clarify assumptions early to avoid ambiguity
- Tie each story to a real business or user value
- Keep the backlog ready for sequencing and iteration planning

## License

This repository does not currently declare a license. If you intend to share or reuse it publicly, consider adding an appropriate open-source license.

## Contact

For questions, suggestions, or collaboration opportunities, please use the repository’s GitHub issues or discussions.

---

This project is a practical starting point for agile planning and can be extended as a workshop, learning lab, or team backlog template.
