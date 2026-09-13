# Research Gantt Chart Skill

Create clear, source-grounded Gantt charts from research proposals, thesis plans, experimental schedules, and task lists.

## What it does

- Extracts dated tasks from plans, including DOCX tables and text containers.
- Groups small tasks into readable research phases.
- Shows phase-level and task-level inclusive month durations.
- Uses consistent colors for project phases without implying planned work has already succeeded.
- Preserves the source timeline and flags questionable sequencing instead of silently rewriting it.
- Produces editable SVG/PDF plus high-resolution raster exports when appropriate.

## Install

Copy this entire folder to one of these locations:

```text
# Personal use across projects
~/.agents/skills/research-gantt-chart/

# Shared use within a repository
<repository-root>/.agents/skills/research-gantt-chart/
```

Restart Codex if the skill does not appear immediately.

## Use

Invoke the skill explicitly in Codex:

```text
$research-gantt-chart
Create a phased Gantt chart from this thesis proposal. Show the duration of every phase and every task.
```

Codex may also select the skill automatically when a request clearly asks for a research timeline or a Gantt chart.

## Contents

```text
research-gantt-chart/
├── SKILL.md
└── agents/
    └── openai.yaml
```

## License

No license has been selected yet. Add a license file before asking others to reuse, modify, or redistribute this project.
