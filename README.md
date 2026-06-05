# Give Your Agent a Diploma

A step-by-step tutorial for beginners who are unfamiliar with coding tools(like me), showing how to build, organize, and use their first Agent Skill.

## Who this tutorial is for

This tutorial is designed for beginners who want to learn Agent Skills but are not very familiar with coding tools, terminal commands, GitHub, or AI coding agents.

There are already many excellent courses, handbooks, and official resources about how to build and deploy Agent Skills, such as AgentSkills.io, Claude’s skill courses, and OpenAI’s handbook for skills in the Agents SDK. However, these materials can still be challenging for people who are new to agents, coding environments, or developer tools.

This tutorial is written for that audience. You do not need a computer science background. The goal is to explain the basic ideas clearly and guide you through small, practical exercises so that you can build and use your first Agent Skill step by step.

## What you will learn

By the end of this tutorial, you will understand:

1. What an Agent Skill is
2. Why Agent Skills are useful
3. How a skill folder is organized
4. How to write a basic `SKILL.md` file
5. How to test whether an agent can use your skill
6. How to build simple reusable skills for everyday tasks

## Agent used in this tutorial

To follow the principle of keeping this tutorial accessible and low-cost, the main demonstrations use Gemini as the default example agent, because Gemini currently provides a free tier or free quota for many basic use cases.

However, this tutorial is not limited to Gemini. If you already have access to Codex or Claude Code, you can also use Codex or Claude Code as your agent. The basic workflow is similar: you create a skill folder, write a `SKILL.md` file, open the project in your agent environment, and test whether the agent follows the skill instructions.

When the setup differs across agents, this tutorial will provide separate steps and commands for Gemini, Codex, and Claude Code.

## Tutorial structure

This tutorial is organized around small exercises. Each exercise introduces one practical skill and one important design principle.

Planned exercises include:

1. Email Polisher
2. Git Commit Writer
3. Code Reviewer
4. Research Paper Summarizer

## Repository structure

```text
docs/        Explanations of key concepts
exercises/   Step-by-step skill-building exercises
templates/   Reusable skill templates
notes/       Glossary and extra notes
```


## Resources

This tutorial is designed to be beginner-friendly and self-contained. You can follow the exercises without reading all of the official documentation first.

However, if you want to learn more about Agent Skills or a specific agent, such as Claude Code or Codex, the following resources are useful.

### Official Agent Skills resources

* [Agent Skills](https://agentskills.io/home)
  A general introduction to what Agent Skills are and why they are useful.

### Claude Code resources

* [Claude: Introduction to Agent Skills](https://anthropic.skilljar.com/introduction-to-agent-skills)
  A Claude-focused course on building, configuring, and sharing skills in Claude Code.

### OpenAI resources

* [OpenAI: Agent Skills for Codex](https://developers.openai.com/codex/skills)
  OpenAI’s guide to using Agent Skills with Codex.

You do not need to understand everything at once. The best way to learn Agent Skills is to build a small skill, test it, revise it, and then build another one.

## Status

This tutorial is currently under construction.
