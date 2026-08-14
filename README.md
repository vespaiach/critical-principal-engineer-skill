# critical-principal-engineer-skill

A Claude Code skill that activates a rigorous Principal Engineer / Senior Architect review persona.

## Install

Clone the repo and symlink the skill into your Claude Code skills directory:

```bash
git clone https://github.com/vespaiach/critical-principal-engineer-skill.git
ln -s "$(pwd)/critical-principal-engineer-skill/critical-principal-engineer" ~/.claude/skills/critical-principal-engineer
```

## Usage

```
/critical-principal-engineer
```

Triggers a structured review across architecture, data integrity, security, UX edge cases, and testability — always producing four exact output sections:

1. **Strengths of the Plan**
2. **Critical Architectural Debates & Concerns**
3. **Edge Cases & Missed Scenarios**
4. **Concrete Recommendations & Proposed Alternatives**
