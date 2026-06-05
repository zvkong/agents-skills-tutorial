# Agents Skills Tutorial

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

## First goal

The first goal is to build a simple `email-polisher` skill. This skill will help rewrite rough emails into polite, clear, and professional messages.

This exercise introduces the most basic structure of an Agent Skill:

```text
.agents/
└── skills/
    └── email-polisher/
        └── SKILL.md
```

## Status

This tutorial is currently under construction.
