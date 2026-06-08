# How to Set Up Your Environment for Agent Skills

In this part, we will set up the basic tools you need to build, edit, and test your Agent Skills more easily.

You may skip this section if you already have basic development environment experience, such as using GitHub, Git, VS Code, or a terminal.

## What you need before starting

Before starting the first exercise, you need the following tools:

1. **A GitHub account**

   GitHub is where you can store your tutorial files online, track changes, and share your work with others.

   Create a GitHub account here: [GitHub Sign Up](https://github.com/signup)

2. **Git installed on your computer**

   Git is a tool that lets you download a repository from GitHub, track your file changes, and upload your changes back to GitHub.

   Download Git here: [Git Downloads](https://git-scm.com/install/)

   Screenshot suggestion: add a screenshot showing the Git download page for Windows, macOS, or Linux.

3. **VS Code installed on your computer**

   I recommend using VS Code as your IDE if you do not already have a preferred editor. VS Code is a free code editor developed by Microsoft. It lets you open project folders, edit files, use extensions, and run terminal commands in one place.

   Download VS Code here: [Visual Studio Code](https://code.visualstudio.com/download)

   Screenshot suggestion: add a screenshot showing the VS Code download page.

4. **One agent environment**

   You need one agent environment to test your skills. In this tutorial, we use Gemini as the default demonstration agent because it currently provides a free tier or free quota for many basic use cases.

   You may also use Codex or Claude Code if you already have access to them. The basic workflow is similar, but the setup steps may differ slightly across agents.

   If you do not want to install VS Code or another IDE, you can still use a regular terminal to run basic commands. However, for beginners, VS Code is recommended because it makes it easier to see folders, edit files, and use the terminal in the same window.

## Step 1: Create your own GitHub repository

After you sign up for a free GitHub account, go to GitHub and create a new repository.

On the GitHub homepage, click **Repositories**, then click **New**.

![Create a new repository](image-1.png)

This repository will be your own practice project for building your first Agent Skill. You can name it whatever you want.

If you would like to follow this tutorial exactly and copy the same commands, use this repository name:

```text
my-first-agent-skill
```

For visibility, choose **Public** if you want other people to see your practice repository. Choose **Private** if you want to keep some secret only to yourself.

For beginners, I recommend leaving the other options unchanged for now. You can add a README, `.gitignore`, or license later.

## Step 2: Open your working folder in VS Code

After creating your GitHub repository, open VS Code.

There are two common ways to open a folder in VS Code.

### Option A: Use the menu

In VS Code, go to:

```text
File -> Open Folder
```

Then choose the folder where you want to store your Agent Skill project.

For example, you may choose:

```text
Desktop
```

or create a new folder such as:

```text
agent-skill-practice
```

### Option B: Use keyboard shortcuts

On Windows or Linux:

```text
Ctrl + K, then Ctrl + O
```

On macOS:

```text
Command + K, then Command + O
```

This opens the folder selection window.

### Option C: Use the terminal

If you already know where you want to create the project, you can also open that folder from the terminal:

```bash
cd ~/Desktop
code .
```

This command opens the current folder in VS Code.

If the `code .` command does not work on macOS, open VS Code, then open the Command Palette:

```text
Command + Shift + P
```

Search for:

```text
Shell Command: Install 'code' command in PATH
```

Run that command, then restart your terminal.

## Step 3: Clone your GitHub repository into VS Code

After creating your GitHub repository online, you need to clone it to your computer.

Cloning means downloading the GitHub repository to your local computer so that you can edit the files.

### Option A: Clone from VS Code

In VS Code, open the Command Palette.

On Windows or Linux:

```text
Ctrl + Shift + P
```

On macOS:

```text
Command + Shift + P
```

Then search for:

```text
Git: Clone
```

Paste your GitHub repository URL. It should look like this:

```text
https://github.com/YOUR-USERNAME/my-first-agent-skill.git
```

Replace `YOUR-USERNAME` with your GitHub username.

Then choose where you want to save the repository on your computer.

After VS Code finishes cloning, it may ask:

```text
Would you like to open the cloned repository?
```

Choose:

```text
Open
```

Now your repository is open in VS Code.

### Option B: Clone from the VS Code terminal

You can also use the terminal inside VS Code.

Open the terminal from the menu:

```text
Terminal -> New Terminal
```

Keyboard shortcut:

On Windows or Linux:

```text
Ctrl + `
```

On macOS:

```text
Control + `
```

Then run:

```bash
cd ~/Desktop
git clone https://github.com/YOUR-USERNAME/my-first-agent-skill.git
cd my-first-agent-skill
code .
```

Replace `YOUR-USERNAME` with your GitHub username.

## Step 4: Check Git synchronization

After opening the repository in VS Code, check whether Git is connected correctly.

Open the terminal in VS Code and run:

```bash
git status
```

If everything is correct, you should see a message similar to:

```text
On branch main
Your branch is up to date with 'origin/main'.
```

This means your local folder is connected to the GitHub repository.

You can also check the GitHub connection by running:

```bash
git remote -v
```

You should see your GitHub repository URL.

For example:

```text
origin  https://github.com/YOUR-USERNAME/my-first-agent-skill.git (fetch)
origin  https://github.com/YOUR-USERNAME/my-first-agent-skill.git (push)
```

### How to save changes to GitHub

After you edit files, you need to save your changes to GitHub.

In VS Code, open the Source Control panel.

You can find it on the left sidebar. It looks like a branch icon.

Keyboard shortcut:

On Windows or Linux:

```text
Ctrl + Shift + G
```

On macOS:

```text
Control + Shift + G
```

Then follow these steps:

1. Review the changed files.
2. Click `+` to stage the files.
3. Write a short commit message.
4. Click `Commit`.
5. Click `Sync Changes` or `Push`.

You can also do the same thing in the terminal:

```bash
git add .
git commit -m "Set up initial agent skill project"
git push
```

## Step 5: Install the necessary VS Code extension

For this tutorial, we use Gemini as the default demonstration agent. To use Gemini inside VS Code, install the Gemini Code Assist extension.

### Install from VS Code

Open the Extensions panel.

You can find it on the left sidebar. It looks like a square blocks icon.

Keyboard shortcut:

On Windows or Linux:

```text
Ctrl + Shift + X
```

On macOS:

```text
Command + Shift + X
```

Search for:

```text
Gemini Code Assist
```

Click:

```text
Install
```

After installation, VS Code may ask you to sign in with your Google account. Follow the sign-in instructions.

### Install from the terminal

If you prefer using the terminal, you can install the extension with:

```bash
code --install-extension Google.geminicodeassist
```

If this command does not work, use the VS Code Extensions panel instead.

### Optional extensions

For this tutorial, Gemini Code Assist is the only required extension if you are using Gemini in VS Code.

You do not need to install many extensions at the beginning. Extra extensions can make the setup more confusing for beginners.

Later, you may choose to install Markdown or Git-related extensions, but they are not necessary for the first Agent Skill exercise.
