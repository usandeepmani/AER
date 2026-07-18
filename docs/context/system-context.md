# 🤖 AER System Context

**Version:** 1.0

## Purpose

This document is the operating manual for AER (AI Engineering & Research).

Any AI assistant working with this repository must follow the standards, workflows and templates defined here.


# Mission

Become an exceptional AI Application Engineer and ultimately an AI Research & Model Engineer through structured learning, Agile practices, and portfolio-quality projects.


# Repository Architecture

| Component | Purpose |
|-----------|---------|
| Repository | Permanent knowledge base |
| GitHub Issues | Work items |
| GitHub Project | Sprint execution |
| Markdown Files | Documentation |
| Projects | Proof of learning |


# Learning Philosophy

Every learning activity should follow these principles:

- Learn deeply rather than quickly.
- Build continuously.
- Reflect on understanding.
- Capture knowledge.
- Apply every concept.
- Prefer official documentation whenever practical.
- Build portfolio-quality projects.

**Every completed issue must produce at least one permanent artifact.**

# Primary Learning Resources

When recommending learning resources, AI assistants should prioritize resources in the following order.

## 1. Official Documentation (Highest Priority)

Examples:

- Python Documentation
- NumPy Documentation
- Pandas Documentation
- PyTorch Documentation
- TensorFlow Documentation
- FastAPI Documentation
- Microsoft Learn
- Azure Documentation
- OpenAI Documentation
- Anthropic Documentation

---

## 2. Official Courses

Examples:

- Microsoft Learn
- DeepLearning.AI
- Hugging Face Course
- Harvard CS50
- fast.ai

---

## 3. High-Quality Books

Examples:

- Fluent Python
- Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow
- Designing Machine Learning Systems
- Mathematics for Machine Learning

---

## 4. Trusted Educational Content

Examples:

- 3Blue1Brown
- Corey Schafer
- Real Python
- StatQuest
- Andrej Karpathy
- Sebastian Raschka

---

## Resource Selection Principles

Whenever recommending resources, AI assistants should:

- Prefer quality over quantity.
- Recommend one primary resource before suggesting alternatives.
- Avoid unnecessary duplication across resources.
- Recommend free resources where practical.
- Recommend Microsoft ecosystem resources where they complement the primary AI learning path.


## Learning Resource Philosophy

The goal is to master concepts rather than complete every available resource.

AI assistants should recommend the minimum set of high-quality resources required to achieve the learning objectives of each sprint.

# AER Learning Cycle

```text
📚 Learn
      ↓
💻 Build
      ↓
🧠 Reflect
      ↓
📖 Capture
      ↓
🚀 Apply
```

No applicable stage should be skipped.


# Agile Workflow

```text
📚 Product Backlog
        ↓
🎯 Sprint Backlog
        ↓
🚧 In Progress
        ↓
👀 Review
        ↓
✅ Done

💡 Parking Lot
```

Sprint Length

- 1 Week


# GitHub Project

## Columns

- 📚 Product Backlog
- 🎯 Sprint Backlog
- 🚧 In Progress
- 👀 Review
- ✅ Done
- 💡 Parking Lot

## Fields

### Built-in

- Status
- Iteration
- Milestone

### Custom

- Type
- Estimate (minutes)

No additional project metadata should be introduced unless there is a demonstrated need.


# Mandatory Templates

The following templates are mandatory and must always be followed.

| Template | Location |
|----------|----------|
| Sprint Template | `sprints/sprint-XX.md` |
| Issue Template | `docs/agile/issue-template.md` |
| Definition of Ready | `docs/agile/definition-of-ready.md` |
| Definition of Done | `docs/agile/definition-of-done.md` |
| Working Agreement | `docs/agile/working-agreement.md` |

AI assistants must follow these templates whenever generating sprint plans, GitHub issues or process documentation.


# Roadmap

The learning roadmap and milestones are maintained in:

`roadmap.md`

Every GitHub Issue must belong to exactly one milestone.


# AI Collaboration Protocol

## Sprint Planning

Before planning a new sprint, request:

### Required

- `docs/context/system-context.md`
- `dashboard.md`
- Latest Sprint document (`sprints/sprint-XX.md`)
- `RETROSPECTIVE.md`

### Optional (only if changed)

- `roadmap.md`
- `DECISIONS.md`

The AI assistant should:

- Review latest sprint outcomes.
- Review retrospective action items.
- Carry forward unfinished work where appropriate.
- Generate the next sprint using the Sprint Template.


## Sprint Execution

Normally, no additional files are required.

If the current conversation does not contain sufficient repository context, request only the minimum required files instead of the entire repository.


## Sprint Review / Retrospective

Before reviewing a sprint, request:

### Required

- `docs/context/system-context.md`
- `dashboard.md`
- Current Sprint document (`sprints/sprint-XX.md`)
- `RETROSPECTIVE.md`

### Optional

- `learning-journal.md`
- Relevant notes
- Project documentation (if the sprint included a project)

The AI assistant should:

- Review completed work.
- Verify Definition of Done.
- Verify artifact production.
- Update sprint metrics.
- Suggest improvements for the next sprint.


## Repository or Process Changes

If changes involve repository structure, workflow, Agile process or documentation standards, request:

- `docs/context/system-context.md`
- `DECISIONS.md`

before making recommendations.


# AI Assistant Rules

Whenever assisting with AER, the AI assistant must:

- Treat repository documentation as the source of truth.
- Follow the roadmap.
- Follow all Agile templates.
- Create outcome-oriented GitHub Issues that follow the official Issue Template.
- Follow the Definition of Ready.
- Follow the Definition of Done.
- Follow the Primary Learning Resources hierarchy defined in this document.
- Recommend one primary resource and optional secondary resources.
- Prefer official documentation whenever practical.
- Generate practical coding exercises and portfolio-quality projects.
- Ensure every completed issue produces at least one permanent artifact.
- Keep GitHub Project metadata minimal.
- Avoid duplicating information across markdown files.
- Request only the minimum files necessary to complete the current task.
- Do not introduce new workflows or processes without user approval.
- Where appropriate, recommend Microsoft ecosystem integrations (ASP.NET Core, Azure, Semantic Kernel, Copilot Studio, Power Platform, SPFx, Microsoft Graph) to complement the primary AI learning path.

# Guiding Principle

Learn deeply. Build continuously. Capture knowledge. Apply what you learn. Improve the system only when genuine friction is discovered.