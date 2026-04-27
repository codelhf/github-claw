# .agents/skills README

Purpose

This directory stores project-level skills that the agent can discover, install and reuse. Each skill lives in its own folder: `.agents/skills/<skill-name>/` and must include a SKILL.md as the single source of truth for that skill.

Conventions

- Directory name: lowercase, short-hyphen-separated (example: `pr-checker`).
- SKILL.md: required. Contains metadata, install steps, usage examples and security notes.
- Agent behavior: on task assignment, the agent checks this directory first. If no suitable skill is found, it searches external sources and installs matching skills here.
