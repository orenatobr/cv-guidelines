---
name: cv-guidelines
description: Build, audit and tailor ATS-friendly CVs and resumes. Use when creating or reviewing a CV/resume, checking ATS compatibility, matching keywords to a job description, writing quantified bullets, formatting sections, or adapting a CV for tech, executive, academic or career-change profiles. Trigger on /cv-guidelines, "CV", "resume", "ATS".
---

# /cv-guidelines

ATS-first CV workflow. Upstream: Paramchoudhary/ResumeSkills (MIT, ~3k stars), the most-starred dedicated resume skill collection on GitHub. Each file in `references/` is one upstream skill; read only the ones the task needs. Never use em dashes in the output.

## Pick the reference

| Task | Read |
|------|------|
| ATS compatibility check, keyword match score | `references/resume-ats-optimizer.md` |
| Analyze a job description, extract keywords | `references/job-description-analyzer.md` |
| Tailor an existing CV to one vacancy | `references/resume-tailor.md` |
| Rewrite weak bullets (action, impact) | `references/resume-bullet-writer.md` |
| Add metrics to bullets | `references/resume-quantifier.md` |
| Build or reorder sections (summary, skills, experience) | `references/resume-section-builder.md` |
| Layout, fonts, file format | `references/resume-formatter.md` |
| Software, data, ML engineer CVs | `references/tech-resume-optimizer.md` |
| Executive / leadership CV | `references/executive-resume-writer.md` |
| Academic CV (PhD, research) | `references/academic-cv-builder.md` |
| Changing career field | `references/career-changer-translator.md` |

## Default flow

1. Get the CV and the target job description. If there is no vacancy, optimize for the role title.
2. Run the ATS reference: single column, standard headings, text-based PDF or .docx, no tables, images or header/footer content.
3. Match keywords to the job description, using the posting's exact terms where the candidate truly has the skill.
4. Rewrite bullets as action + scope + measurable result. Never invent a number, employer, date or credential; ask for it.
5. Report what changed, the ATS risks left, and the keyword gaps.
