name: <skill-name>
version: 0.1.0
source: <original-source-url>
license: <license-or-unknown>
fetched: 2026-04-27
tags: [example]
summary: One-line description of what this skill does

description: |
  Detailed description, intended usage, and limitations.

usage:
  - example: |
      # minimal usage example
      echo "run skill"

install:
  - steps: |
      # reproducible install steps, e.g.:
      # 1. git clone <repo> .
      # 2. ./install.sh
  - deps:
      - python>=3.8

security:
  - risk: "Notes about security risks (downloads, executing binaries, network access)"
  - sandbox: "Recommended sandbox or manual confirmation steps before running"

files:
  - scripts/: "List of key files or directories in this skill"

notes:
  - maintainer: "<optional maintainer or contact>"
  - changelog: "agent will append an entry after installation"
