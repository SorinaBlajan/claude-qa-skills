# claude-qa-skills
Claude Code skills and agents for QA workflows — bug reports, test cases, and PR reviews.

# Claude Code QA Skills & Agents

A collection of Claude Code skills and custom agents designed for QA engineers.
Stop repeating yourself — write it once, use it everywhere.

## What's included

### Skills
| Skill | Description |
|-------|-------------|
| `bug-report` | Generates a structured bug report with severity, steps to reproduce, expected vs actual results |
| `pr-description` | Writes consistent pull request descriptions summarizing what changed and why |

### Agents
| Agent | Description |
|-------|-------------|
| `test-cases` | Writes structured test cases, test suites, and acceptance criteria for features or bug fixes |

## Requirements

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed
- A terminal with access to your home directory

## Installation

### Mac / Linux
```bash
git clone https://github.com/SorinaVladu/claude-qa-skills.git
cp -r claude-qa-skills/skills ~/.claude/
cp -r claude-qa-skills/agents ~/.claude/
```

### Windows
```cmd
git clone https://github.com/SorinaVladue/claude-qa-skills.git
xcopy /E /I claude-qa-skills\skills %USERPROFILE%\.claude\skills
xcopy /E /I claude-qa-skills\agents %USERPROFILE%\.claude\agents
```

Then **restart Claude Code** for the skills and agents to load.

## Folder structure
.claude/
├── agents/
│   └── test-cases.md
└── skills/
├── bug-report/
│   └── SKILL.md
└── pr-description/
└── SKILL.md
