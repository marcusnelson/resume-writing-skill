# Resume Craft — Claude Skill

A Claude skill that applies professional resume writing craft to your content — strong bullets, a summary that earns the next read, and ATS hygiene that doesn't sacrifice the human skim.

**The job of a resume is to win the next conversation.** Not to list everything. Not to beat a robot. This skill helps you write one that does.

## The Core Insight

**The human is the filter, not the machine.** Roughly 92% of recruiters still review resumes by hand. ATS systems mostly store and rank — a person decides. So the work is ~80% reader craft, ~20% machine hygiene. This skill optimizes for the skimmer first.

## What It Does

### Bullet Craft
Rewrites bullets using the **action → mechanism → result** formula:
- ❌ "Responsible for social media growth."
- ✅ "Grew social audience 1,945% in two years by building an MVP recognition program."

Every bullet gets the "so what" test. If the result can be stripped without losing anything, it wasn't doing work.

### Summary Writing
Three or four lines. Who you are, the scale you operate at, the one proof that earns the rest of the read. Not an objective statement. Not a personality quiz.

### ATS Optimization
- Mirrors the job description's actual vocabulary into real context — no stuffing
- Flags what still breaks parsers: tables, text boxes, multi-column layouts, header/footer content, image-based text
- Corrects the myths: PDFs aren't unreadable, one page isn't mandatory at senior level, there's no magic ATS score to beat

### Tailoring Per Role
1. Read the job post for language and knockout requirements
2. Pick the angle — which two or three credentials carry *this* role
3. Mirror vocabulary honestly into summary, competencies, and bullets
4. Quantify every claim you can defend; flag gaps rather than inventing
5. Re-skim the top third — if it doesn't win six seconds, fix that first

### What Gets Cut
Resume tax that costs space without adding signal: "References available on request," full street addresses, objective statements, soft-skill adjectives with nothing behind them.

## What It Doesn't Do

Layout, fonts, and file rendering are a separate job — use the `resume-format` skill for `.docx` and PDF output. This skill decides what the resume *says*. That one decides how it *looks*.

## Install

Download `resume-craft.skill` and install it in Claude:

**Claude Chat (claude.ai)**
1. Open **claude.ai** → **Customize** → **Skills**
2. Click **Add Skill** and upload the `.skill` file

**Claude Code (CLI / desktop app)**
1. Copy to `~/.claude/skills/` (global) or `.claude/skills/` (project)
2. Load with `@path/to/resume-craft.skill`

Triggers on: "rewrite my resume," "tighten this bullet," "make this ATS-friendly," "why am I not getting callbacks," "tailor my resume to this job post," or any request to write, edit, or critique resume content.

## Pair With

- **[resume-format](https://github.com/marcusnelson/resume-format-skill)** — renders the finished content into a polished `.docx` or branded PDF, with automatic page-break auditing.

## Pre-Send Checklist

- [ ] Top third makes the case alone
- [ ] Majority of bullets quantified, none invented
- [ ] Role's key phrases mirrored, not stuffed
- [ ] Single column, standard headings, real text
- [ ] No tables / text boxes / header-footer content
- [ ] Length matches seniority
- [ ] Every claim defensible in an interview

## License

MIT

## Author

[Marcus Nelson](https://gofullnelson.com)
