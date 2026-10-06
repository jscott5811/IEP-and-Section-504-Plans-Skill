# IEP and Section 504 Plans Skill

An AI skill that helps parents understand and secure school supports for a
student with a disability — grounded only in verified U.S. Department of
Education sources.

## What it covers

- **IEPs (Individualized Education Programs)** under the Individuals with
  Disabilities Education Act (IDEA): specialized instruction and measurable
  annual goals for students eligible for special education.
- **Section 504 plans** under Section 504 of the Rehabilitation Act of 1973:
  civil rights-based accommodations that give students equal access to the
  general learning environment.
- **The parent process:** gather medical diagnoses and evaluations, submit a
  written evaluation request to the school district, and keep organized
  records of all correspondence and accommodations.

Federal rules apply in all 50 states. Where a detail is set by the state or
district (exact evaluation timelines, local 504 procedures), the skill says
so and tells you to verify locally.

## Install

```sh
npx skills add jscott5811/IEP-and-Section-504-Plans-Skill
```

## Layout

```
skills/iep-and-504-plans/
├── SKILL.md                          # the skill: purpose, workflow, rules
└── references/
    ├── verified-sources.md           # every ED/federal source, with links
    └── parent-action-checklist.md    # the 3-step process, sample letter, log
```

## Sources

All claims trace to U.S. Department of Education publications and federal
regulations — see `skills/iep-and-504-plans/references/verified-sources.md`
for the full list with links. Key sources:

- U.S. Dept. of Education, OCR + OSERS, *Long COVID under Section 504 and
  the IDEA* (July 26, 2021)
- U.S. Dept. of Education, OCR, *Parent and Educator Resource Guide to
  Section 504 in Public Elementary and Secondary Schools* (Dec 2016)
- IDEA regulations, 34 CFR Part 300

## Note

This skill provides information, not legal advice. For disputes, use the
district's procedural safeguards notice and your state's free Parent
Training and Information Center.

## License

MIT — see [LICENSE](LICENSE).
