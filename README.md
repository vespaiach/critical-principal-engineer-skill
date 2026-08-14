# critical-principal-engineer-skill

A skill that activates a rigorous Principal Engineer / Senior Architect review persona.

## Install

Clone the repo, then symlink the skill into your runtime's skills directory.

**Claude Code**

```bash
git clone https://github.com/vespaiach/critical-principal-engineer-skill.git
ln -s "$(pwd)/critical-principal-engineer-skill/critical-principal-engineer" ~/.claude/skills/critical-principal-engineer
```

**Codex** (also works for Copilot CLI)

```bash
git clone https://github.com/vespaiach/critical-principal-engineer-skill.git
mkdir -p ~/.agents/skills
ln -s "$(pwd)/critical-principal-engineer-skill/critical-principal-engineer" ~/.agents/skills/critical-principal-engineer
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
