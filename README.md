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

## Available Skills

| Skill                      | Description                                                                                             | Location                                                        |
| -------------------------- | ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Writing Tests (Go)         | Write and fix Go unit tests: table-driven tests, mocks, coverage checks                                 | [`writing-tests-go-projects/`](./writing-tests-go-projects/)   |
| Writing Dockerfiles (Go)   | Create optimized multi-stage Dockerfiles for Go apps, static builds, and minimal runtime images         | [`writing-dockerfile/`](./writing-dockerfile/)                 |
| Handle Logging (Go)        | Structured logging guidance: `slog`/`zap`, log levels, request logging, and what not to log             | [`handle-logging/`](./handle-logging/)                         |
| Go Context                 | Best practices for `context.Context`: signatures, derivation, cancellation, and value usage            | [`go-context/`](./go-context/)                                 |
| Naming Convention (Go)     | Idiomatic naming rules for packages, types, functions, variables, constants, and receivers             | [`naming-convention/`](./naming-convention/)                   |
| Go Style Core              | Core style principles: clarity, simplicity, gofmt, nesting, naked returns, and semicolons               | [`go-style-core/`](./go-style-core/)                           |
| Go Linting                 | Linting setup and recommendations: `golangci-lint`, recommended linters, and CI integration examples     | [`go-linting/`](./go-linting/)                                 |

## References

- External reference repo with additional Go skills and examples: https://github.com/cxuu/golang-skills
