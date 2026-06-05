# What is an Agent Skill?

Before we explain Agent Skills, we first need to understand what an agent is.

Many people first understand AI through chatbots such as ChatGPT, Gemini, or Claude. A chatbot can be thought of as a consultant you hire. You ask questions, and it gives you suggestions, explanations, drafts, or plans. It may be very knowledgeable, but in most cases it only responds inside the chat. It does not directly organize your files, edit your project, run commands, or complete tasks in your working environment.

In this sense, the chatbot has a “brain,” which usually refers to the large language model, or LLM, behind it. However, by itself, the chatbot does not have a “body” that allows it to act on your computer or inside your project.

An agent gives that brain a body.

An agent can use tools, read files, edit code, run commands, inspect project folders, and help complete tasks under your permission. Instead of only giving advice, an agent can help do the work. A simple way to think about it is this:

```text
Chatbot = a consultant who gives advice
Agent   = a worker who can help complete tasks
```

Of course, an agent should not act without control. It still needs instructions, permissions, and boundaries. But compared with a chatbot, an agent is designed to take action, not just answer questions.

## What is an Agent Skill?

Now we can ask: what is an Agent Skill?

Imagine the agent as a new Ph.D. student joining your research group. This student is smart and already has many general abilities: writing, reading papers, basic coding, summarizing information, and doing some mathematical reasoning. However, if you want this student to work well in your specific research area, general intelligence is not enough.

They need to learn your preferred workflow, your writing style, your file structure, your research conventions, and the specific rules for producing work that fits your expectations.

You could let the student figure everything out by trial and error. They might search online, read examples, and slowly learn what you want. But this would take time, and the result may not be stable.

A better approach is to give the student a short guide that says:

```text
When you are doing this kind of task,
follow these instructions,
use these examples,
respect these constraints,
and produce the output in this format.
```

That guide is similar to an Agent Skill.

An Agent Skill is a reusable package of instructions that teaches an agent how to perform a specific type of task in a specific way. A skill can tell the agent when to use it, what rules to follow, what output format to produce, and what resources or scripts are available.

In this tutorial, we will walk through several simple skill exercises to help you understand the basic idea:

```text
A skill gives an agent task-specific mini-handbooks.
```

Once you understand this idea, you can build skills for many different tasks, such as writing emails, generating Git commit messages, reviewing code, summarizing research papers, or preparing project reports.

## What kind of work is suitable for an Agent Skill?

Agent Skills are most useful when a task has repeated patterns, rules, or procedures.

1. **Repeated instructions**

   A skill is useful when you often find yourself repeating the same instructions to the agent. For example, you may repeatedly ask the agent to follow a specific output format, use a certain feedback structure, avoid changing the original meaning of a text, or organize results in a particular way. Instead of typing these rules again and again, you can put them into a skill.

2. **Standard operating procedures**

   A skill is also useful when your work has a standard operating procedure, or SOP. For example, if you review code using the same checklist every time, summarize papers using the same structure, or polish emails according to the same tone and format, these repeated procedures can become skills.

In general, if you can describe your task as “when doing this type of work, always follow these rules,” then it is probably a good candidate for an Agent Skill.
