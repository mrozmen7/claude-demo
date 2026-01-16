# CLAUDE.md — Company Rules

# CLAUDE.md — Company Rules

## Purpose
This file defines how work is done in this repository.
All contributors (humans or AI) must follow these rules.

## Branching Rules
- Never commit directly to `main`
- Always create a feature branch from `main`
- Branch naming:
  - docs/*
  - feat/*
  - fix/*

## Change Rules
- Only modify files allowed by the issue scope
- If the issue says "README only", do not touch other files

## Workflow
1. An issue is created
2. A branch is created from `main`
3. Changes are committed to the branch
4. A Pull Request (PR) is opened
5. CI must pass
6. PR is reviewed and merged

## CI Rules
- CI must be green before merge
- CI may block missing files or invalid changes

## Forbidden
- Pushing directly to `main`
- Bypassing CI
