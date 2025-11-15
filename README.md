# TÂCHES Prompts

Slash commands and prompt systems for Claude Code.

## Quick Start

```bash
# Clone the repo
git clone https://github.com/yourusername/taches-cc-prompts.git
cd taches-cc-prompts

# Install meta-prompting
cp meta-prompting/*.md ~/.claude/commands/

# Install todo management
cp todo-management/*.md ~/.claude/commands/
```

All commands work globally. Project-specific data (prompts, todos) lives in each project's working directory.

## Available Prompts

### [Meta-Prompting](./meta-prompting/)

A systematic approach to building complex software by delegating prompt engineering to Claude itself. Instead of telling Claude what to do, you tell Claude what you want, and it figures out how to ask itself to do it.

Perfect for complex refactoring, new features, and multi-step tasks where you want rigorous specifications without manually crafting detailed prompts.

### [Todo Management](./todo-management/)

Capture ideas mid-conversation without losing focus. When you spot a bug, think of a feature, or notice something to refactor - but don't want to derail your current work - `/add-to-todos` captures it with full context. Later, `/check-todos` resumes exactly where you left off.

Perfect for staying focused while building a backlog of improvements, features, and research tasks that won't be forgotten.

---

More prompts coming soon.

—TÂCHES
