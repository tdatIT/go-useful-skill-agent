# Go Useful Skill Agent

Collection of AI agent skills for Go development.

## Quick Start

### Install This Skill

Install this skill collection from GitHub using the `skills` CLI:

```bash
npx skills add tdatIT/go-useful-skill-agent
```

### Skill Usage

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
| Go Linting                 | Linting setup and recommendations: `golangci-lint`, recommended linters, and CI integration examples     | [`go-linting/`](./go-linting/)
| CQRS Architecture (Go)        | Implementing CQRS architecture in Go: project structure, interfaces, decorators, and application scope    | [`go-clean-cqrs-architecture/`](./go-clean-cqrs-architecture/)
                        |

## References

- External reference repo with additional Go skills and examples: https://github.com/cxuu/golang-skills
