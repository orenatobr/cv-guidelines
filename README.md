# cv-guidelines

An ATS-first workflow for CVs and resumes. `SKILL.md` routes each task (ATS check, job description analysis, tailoring to one vacancy, bullet rewrites, quantifying impact, section building, formatting, and tech, executive, academic or career-change profiles) to one of eleven reference files. The agent reads only the references the task needs. The references come from Paramchoudhary/ResumeSkills (MIT), see `NOTICE.md`.

## Install

For Claude Code, copy the skill folders into your personal skills directory:

```bash
git clone https://github.com/orenatobr/cv-guidelines.git
mkdir -p ~/.claude/skills
cp -R cv-guidelines/skills/* ~/.claude/skills/
```

Start a new Claude Code session. Skills load from the `description` in each `SKILL.md`, so they trigger on their own and can also be called by name.

Other agents: each skill is a folder with a `SKILL.md` (YAML frontmatter plus Markdown). Tools that read the Agent Skills format can load `skills/` as it is. For the rest, paste the body of the `SKILL.md` into the agent's instruction file.

## Usage

Invoke `/cv-guidelines` with a CV and, ideally, a job description. It also triggers on "CV", "resume" and "ATS".

## Requirements

Nothing beyond an agent that loads skills.

## What is in this repo

| Path | Purpose |
|------|---------|
| `skills/cv-guidelines/` | The `cv-guidelines` skill. |
| `CHANGELOG.md` | Notable changes, in Keep a Changelog format. |
| `AGENTS.md` | Rules for AI agents that edit this repo. |

## Contributing

`main` is protected: changes land through a pull request with one approval. See [AGENTS.md](AGENTS.md) for the conventions.

## License

MIT, see [LICENSE](LICENSE).
Third-party material is credited in [NOTICE.md](NOTICE.md).

