# dashME

A personal planning dashboard. It bundles todos, ideas and a weekly schedule, and it learns how long my tasks really take.

> **Status:** personal project, runs as a single local process. The source code is private. This repository contains the README and the architecture write-up only.

## What it does

- Keeps todos, ideas, fixed blocks and free time slots in one place.
- **Calibrates time estimates.** When I finish a todo and log the real hours, the tool learns a correction factor per category and corrects future estimates.
- **Plans the week.** A scheduler places todos into free slots that match the energy each task needs, and reports honestly how many hours are short.
- Uses an LLM to structure free-text input and to give feedback.
- Can bundle other personal data sources through MCP (todos, calendar, notes, a notes app), as a memory aid.

## Stack

Python, FastAPI, SQLModel, SQLite, a single-page web UI, an LLM API, MCP.

## Documentation

- [ARCHITECTURE.md](ARCHITECTURE.md): data model, calibration loop, scheduler.

## License

All rights reserved. No source code is published here.
