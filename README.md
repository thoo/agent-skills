# My Agent Skills

A Claude Code plugin marketplace containing custom skills.

## Available Skills

| Skill | Description |
|-------|-------------|
| `python-code-review` | Review Python code changes in merge requests and pull requests |

## Installation

### Add the Marketplace

```
/plugin marketplace add thoo/agent-skills
```

### Install a Skill

```
/plugin install python-code-review@my-agent-skills
```

## Usage

Once installed, use the skill by running:

```
/python-code-review
```

Or trigger it naturally by asking Claude to review Python code, check a PR, or do a code review.

## Validation

You can validate skills using the [agentskills](https://github.com/agentskills/agentskills) reference library:

```bash
uvx --from "git+https://github.com/agentskills/agentskills.git#subdirectory=skills-ref" skills-ref validate path/to/skill
```

## License

MIT
