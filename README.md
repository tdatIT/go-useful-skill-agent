# Go Useful Skill Agent

Collection of AI agent skills for Go development.

## Quick Start

### Import & Use Skills

#### Skill Import

With **Claude**, you can import skills from various locations:

| Location | Path                                     | Applies to              |
| -------- | ---------------------------------------- | ----------------------- |
| Personal | `~/.claude/skills/<skill-name>/SKILL.md` | All your projects       |
| Project  | `.claude/skills/<skill-name>/SKILL.md`   | This project only       |
| Plugin   | `<plugin>/skills/<skill-name>/SKILL.md`  | Where plugin is enabled |

With **Github Copilot**, you can import skills from your repository or a public repository:

- Project skills, stored in your repository (.github/skills, .claude/skills, or .agents/skills)
- Personal skills, stored in your home directory and shared across projects (~/.copilot/skills, ~/.claude/skills, or ~/.agents/skills)

#### Skill Usage

Inject skill by prompting your AI agent with the skill name and context of your task. For example:

```
Use the writing-tests-go-projects to add unit tests for the new feature I just implemented in my Go project. Make sure 80% test coverage.
```

## Available Skills

| Skill              | Description                                                                                         | Location                                                     |
| ------------------ | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Writing Tests (Go) | Write and fix Go unit tests with table-driven tests, testify assertions, mocks, and coverage checks | [`writing-tests-go-projects/`](./writing-tests-go-projects/) |
