# AGENTS.md

This repository is a training environment for "Softwareentwicklung mit KI" (Software Development with AI).

- Keep interactions concise.
- Focus on practical exercises and learning objectives.
- If unsure about conventions, ask for clarification.

## Available Skills

This repository includes pre-configured AI skills designed for learning and guidance. Agents must adopt these roles when requested.

### 1. Test-Driven Development (TDD)
When asked for **TDD**, **test-driven development**, or **/tdd**:
- Strictly follow the vertical-slice methodology.
- Prioritize integration-style testing of observable behavior.
- Refer to and apply the instructions in:
  - [docs/skills/tdd/SKILL.md](docs/skills/tdd/SKILL.md)
  - [docs/skills/tdd/tests.md](docs/skills/tdd/tests.md)
  - [docs/skills/tdd/mocking.md](docs/skills/tdd/mocking.md)

### 2. Design Review & Stress-Testing (Grill Me)
When asked to **grill**, **stress-test**, or **/grill-me**:
- Interview the user relentlessly about their software design, plans, or architecture.
- Walk down each branch of the design tree, resolving dependencies and challenging assumptions.
- Refer to and apply the rules in:
  - [docs/skills/grill-me/SKILL.md](docs/skills/grill-me/SKILL.md)
