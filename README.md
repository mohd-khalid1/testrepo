# TODO: Project name

TODO: One-line description of the project.

## Status

This is a sample README. Product details have not been added yet.

There is no application code in this repository today. Sections below are placeholders to fill in later.

## What this project will do

TODO: Describe the purpose of the project.

## Prerequisites

TODO: List required tools and versions.

## Install

TODO: Install command.

## Configure

TODO: Configuration steps and required settings.

## Run

TODO: Run command.

## Test

TODO: Test command.

## Project layout

What exists in the repository today:

```
.
├── README.md
└── .cursor/
    └── agents/
        ├── architect.md
        ├── developer.md
        ├── quality-assurer.md
        └── documentation-king.md
```

TODO: Application layout will be added when source code exists.

## API documentation

API documentation has not been written yet.

When HTTP APIs exist, the OpenAPI spec is expected at `docs/openapi.yaml`. That file is not in the repository today.

## Diagrams

Diagrams have not been written yet.

When they exist, draw.io diagrams are expected under `docs/diagrams/`. That folder is not in the repository today.

## Project agents

Custom Cursor subagents live under `.cursor/agents/`. Invoke one by name in chat:

| Invoke | File | Role |
| --- | --- | --- |
| `/architect` | `.cursor/agents/architect.md` | Gathers requirements and writes a system design with tradeoffs before implementation. Does not implement code. Saves designs under `docs/architecture/`. |
| `/developer` | `.cursor/agents/developer.md` | Implements features, fixes bugs, and adds test cases. Does not edit the README, OpenAPI spec, or diagrams. |
| `/quality-assurer` | `.cursor/agents/quality-assurer.md` | Independently verifies an implementation, runs the relevant tests, and reports actual results. Does not implement or fix code. |
| `/documentation-king` | `.cursor/agents/documentation-king.md` | Generates and updates the README, OpenAPI/Swagger API docs, and draw.io diagrams from the codebase. Does not design features or change application behavior. |
