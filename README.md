# agent-skills

A collection of agent skills I've built for my use with my personal agents.

## Installation

```bash
npx skills add --global Silvenga/agent-skills
```

## Skills

- `copilot`: For high touch or complex workflows, assuming Human-in-the-loop. Built upon aviation concepts to prevent the two extremes - a Yes-Man (Sycophancy) and runaway autonomous actions. Why use an LLM if it's just going to be a glorified natural language engine?
- `conventions-writing`: A documentation writing style for AI agents - impersonal, ASCII-only, markdown-native prose with explicit punctuation, structure, and formatting rules. Matches my personal style condensed into a skill.
- `conventions-code-rust`: Style and structure conventions for Rust modules, visibility, errors, and tests.
- `conventions-frontend`: Opinionated style conventions for frontend projects (TypeScript, TailwindCSS, Vite, Vitest, Oxlint/Oxfmt).
- `conventions-skills`: Best practices for agents writing skills.
- `hindsight`: A personal skill for Hindsight (Agent Memory), optimized for MCP use (hardness portable).

## Agents

- `coding`: A baseline default to build coding agents.
- `research`: A research agent, designed to iteratively research a topic. Optimized for web searching where source bias/quality is not obvious.
