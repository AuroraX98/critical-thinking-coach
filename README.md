# Critical Thinking Coach

Practice critical thinking using a real situation from your own life, one small question at a time. The coach helps you examine your evidence and reasoning, reach your own conclusion, and decide what to check next. It does not pretend to know hidden causes or tell you what your life “really” means.

## Compatible AI assistants

This is a **portable, instruction-based Agent Skill**, intended for **ChatGPT, Claude, and other AI agents that support user-supplied `SKILL.md` packages**. It is not a standalone app or an OpenAI-only integration.

The coaching package contains Markdown instructions and references, plus optional OpenAI UI metadata. It has **no required scripts, API keys, external services, or ChatGPT visualization dependency**. The assistant's own tools and permissions determine whether it can check a source; the coach must say when it cannot verify something.

| Platform | How to use it |
| --- | --- |
| ChatGPT | Where Skills and uploads are enabled, use **Plugins → Skills → Create → Upload from your computer**. Review the package before installing. See [OpenAI's Skills guide](https://help.openai.com/en/articles/20001066-skills-in-chatgpt). |
| Claude | ZIP the `critical-thinking-coach` folder, keeping `SKILL.md` and `references/` together, then use **Customize → Skills → Create skill → Upload a skill**. Claude's Skills feature has its own availability and code-execution settings, even though this package contains no executable code. See [Claude's Skills guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude). |
| Other compatible agents | Follow that agent's custom-skill installation instructions and retain the package's relative reference paths. Support for optional `agents/openai.yaml` metadata varies. |

If an assistant does not support skill installation, you can provide the instructions and relevant references as conversation context. That is **manual prompting**, not native installation or a guarantee of automatic activation.

Installation methods vary by product, account, and administrator settings. Cross-platform suitability is based on the package format and documented platform capabilities, **not a claim that this release has been tested on every platform or model**.

## How it works

Start with a situation you want to understand. Clarify the question and what matters to you, then work through these checks incrementally:

| Check | What you practice |
| --- | --- |
| Evidence | Separate what you observed from how you interpret it. |
| Source quality | Ask how well placed a source is to know this particular claim. |
| Assumptions | Notice what your conclusion takes for granted. |
| Reasoning | Check whether the evidence supports the conclusion and its scope. |
| Alternatives | Consider other explanations or useful options. |
| Uncertainty | Identify what remains unknown and what could change your mind. |

The coach waits for your answer, offers brief evidence-linked feedback, and lets you revise your reasoning. When useful, it helps you design a small, safe test. It follows your pace rather than presenting a long questionnaire or starting fictional scenarios automatically.

## Try it

After installing the `critical-thinking-coach` folder in a skill-capable assistant:

```text
Use the Critical Thinking Coach skill. Ask me about a situation from my life and help me think it through, one small question at a time.
```

Or bring a specific situation:

```text
Use the Critical Thinking Coach skill. I’m deciding whether to change my study routine. Help me clarify what evidence I need before deciding.
```

These sample requests are generic, not records of anyone’s private session. You can omit names, anonymize details, decline a question, stop, or change focus. Fictional practice is available only if you request or accept it.

## Feedback and limits

Feedback concerns the reasoning you demonstrate, not your intelligence, personality, or diagnosis. Scores are optional and informal; no overall intelligence score or validated assessment is provided. An assisted retry does not prove independent mastery, and practice does not guarantee lasting transfer.

Ask for **assess-only** if you want observations on your reasoning without hints or coached retries. Qualitative confidence is welcome; percentages are optional. Strong evidence can justify confidence, while “not enough information yet” can be a useful conclusion when its limits are clear.

The coach does not invent facts, verify sources it has not checked, infer other people’s motives, or pressure you to disclose private details. It is not a substitute for qualified professional advice or factual investigation. Personal session details must not be reused in public examples without specific authorization.

## Files

- [Skill instructions](critical-thinking-coach/SKILL.md)
- [Assistant metadata](critical-thinking-coach/agents/openai.yaml)
- [Real-life practice prompts](critical-thinking-coach/references/exercises.md)
- [Quality checklist and optional scoring anchors](critical-thinking-coach/references/quality-checklist.md)
- [Evidence notes](critical-thinking-coach/references/evidence-notes.md)

The evidence notes describe research that informed the design. None of those studies tested this skill.
