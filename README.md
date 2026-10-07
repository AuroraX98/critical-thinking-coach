# Critical Thinking Coach

Critical Thinking Coach is a skill for practicing one reasoning move at a time through short, fictional scenarios and evidence-linked feedback. It assesses what a response shows without inferring intelligence, personality, diagnosis, or general ability.

## Six reasoning focuses

- Separate a claim from its supporting evidence.
- Consider alternative causes.
- Check base rates and numerical denominators.
- Trace sources and seek independent corroboration.
- Represent an opposing position fairly.
- Match confidence to evidence and revise when evidence strengthens.

## Using the skill

After installing the `critical-thinking-coach` folder in a skill-capable assistant, try a coaching session with this prompt:

```text
Use $critical-thinking-coach for a short practice session. Give me one scenario at a time and wait for my answer.
```

A typical session is approximately 5–8 minutes as a practical estimate, not a measured duration. Coaching usually moves from a baseline attempt to a supported retry, then a fresh scenario that calls for the same reasoning move in a different context. You can stop, skip, change focus, switch modes, or request a hint at any time.

To ask for assessment without coaching, use:

```text
Use $critical-thinking-coach in assess-only mode. Give me one scenario at a time and wait for my answer. Give informal observations for each reasoning focus you assess, without hints, lessons, or coached retries.
```

Observations are informal and tied to the reasoning shown in each case. There is no overall intelligence score, and the anchors are not a validated assessment. A supported retry is practice, not independent evidence of mastery. Do not treat practice as proof of lasting learning or transfer.

## Repository files

```text
README.md
critical-thinking-coach/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── evidence-notes.md
    ├── quality-checklist.md
    └── exercises.md
```

- [Skill instructions](critical-thinking-coach/SKILL.md)
- [Assistant metadata](critical-thinking-coach/agents/openai.yaml)
- [Evidence notes](critical-thinking-coach/references/evidence-notes.md)
- [Quality checklist and scoring anchors](critical-thinking-coach/references/quality-checklist.md)
- [Prepared exercises](critical-thinking-coach/references/exercises.md)

The reference exercise keys are for the tutor and are withheld until the learner attempts a case. The evidence notes describe research that informed design choices; none of the cited studies tested this skill.
