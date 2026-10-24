# AI Customer Support Chatbot

## Project Title

**Development of an AI-powered chatbot for customer support**

## 1. Project Overview

This project aims to develop a configurable AI-powered customer support chatbot that can be used by multiple businesses.

The system is designed to answer common customer questions, use business-specific information, and reduce repetitive tasks for customer support staff.

Each business will have its own chatbot configuration, knowledge sources, and support rules.

## 2. Project Objectives

The main objectives are:

- Develop a configurable customer support chatbot.
- Support multiple businesses with separate configurations.
- Allow businesses to manage chatbot settings and knowledge sources.
- Process customer questions using an appropriate response-generation method.
- Provide fallback handling for questions that cannot be answered reliably.
- Evaluate response accuracy, reliability, and performance.

## 3. Project Team

| Team Member | Role | Responsibilities |
|---|---|---|
| Balnur | Programmer / Developer | Backend, frontend, API development, integration, and testing |
| Karina | Project Manager | Project planning, task management, risk management, and progress tracking |
| Karakat | System Analyst | Requirements analysis, research, architecture diagrams, and acceptance criteria |

## 4. Target Users

The main users of the system are:

- **Business Administrators:** Configure chatbot settings and business information.
- **Customers:** Ask questions and receive chatbot responses.
- **Support Operators:** Handle customer questions that require human assistance.

## 5. Planned System Features

- Business-specific chatbot configuration.
- Customer question processing through an API.
- Support for business-specific FAQs and knowledge sources.
- Configurable greetings and response rules.
- AI-assisted answer generation.
- Fallback handling for unsupported questions.
- Separation of data and settings between businesses.
- A web-based interface for chatbot interaction.

These features describe the planned system and are not all implemented at the current stage.

## 6. Technology Stack

The following technologies are being considered or used during project development:

| Area | Technology |
|---|---|
| Backend | Python; FastAPI under consideration |
| Frontend | HTML, CSS, JavaScript |
| Database | PostgreSQL under consideration |
| AI Response Generation | FAQ-based methods, direct LLM API, or RAG (under evaluation) |
| Testing | Python, Pytest (planned) |
| Version Control | GitHub |
| Project Management | YouTrack |
| Architecture Diagrams | draw.io |

Final technology choices will be confirmed during implementation.

## 7. Repository Structure

```text
AI-Customer-Support-Chatbot/
├── docs/
│   ├── proposal/
│   ├── research/
│   ├── requirements/
│   ├── architecture/
│   ├── evaluation/
│   └── management/
├── prototype/
├── backend/
├── frontend/
├── tests/
├── config/
└── README.md
```

## 8. Project Documentation

Project materials are organized in the `docs/` directory:

- `docs/proposal/` — Project Proposal.
- `docs/research/` — Literature Review and technology comparisons.
- `docs/requirements/` — Functional and non-functional requirements, acceptance criteria, and stakeholder needs.
- `docs/architecture/` — System Context, Use Case, and Component diagrams.
- `docs/evaluation/` — Verification and Evaluation Plan.
- `docs/management/` — Project Plan, Risk Register, and Supervisor Feedback.

## 9. Project Management

Project tasks, responsibilities, priorities, and progress are managed using YouTrack.

**YouTrack Project:** [View Project Tasks](https://configurable-chatbot.youtrack.cloud/agiles/204-1/current)

GitHub is used for source code, documentation, version control, and tracking individual team contributions.

## 10. Current Project Status

**Stage:** First Pre-Defense — October 24, 2026

At this stage, the project focuses on:

- Project proposal and scope definition.
- Literature review.
- Existing systems and technology comparison.
- Initial functional and non-functional requirements.
- System architecture design.
- UI prototype preparation.
- Verification and evaluation planning.
- Task management and team coordination.

The complete chatbot application is still under development.

## 11. Planned Testing

The project will be evaluated through:

- Functional testing.
- API testing.
- Integration testing.
- Security and business-isolation testing.
- Response accuracy evaluation.
- Performance testing.
- Fallback behavior testing.

The detailed plan is available in `docs/evaluation/Verification_Plan.md`.

## 12. Expected Outcome

The expected result is a configurable AI-powered customer support chatbot prototype that supports multiple businesses, processes customer questions, and provides reliable response handling based on business-specific information.

## 13. Academic Information

**University:** Astana IT University  
**School:** School of Software Engineering  
**Project Type:** Team Diploma Project  
**Year:** 2026
