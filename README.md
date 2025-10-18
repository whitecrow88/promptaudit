# PromptAudit Template

PromptAudit is a lightweight review framework that helps human reviewers and agentic coding systems stress-test prompts and supporting project documentation. Use it to uncover contradictions, clarify intent, and turn findings into prioritized fixes so teams can move from messy specs to shippable instructions quickly.

## Highlights
- Repeatable audit flow that is tuned for prompt engineering work.
- Separates discovery, analysis, and remediation for clearer decision making.
- Captures confidence and follow-up actions so findings stay actionable.
- Plain Markdown that drops into any repository or shared workspace.

## Template Sections
1. **Summary of Issues** - Capture contradictions, missing context, and confusing guidance.
2. **Analysis / Context** - Explain the underlying causes (tone drift, acceptance criteria gaps, etc.).
3. **Suggested Rewrites / Additions** - Propose improved copy, prompts, or specs in Markdown/code blocks.
4. **Confidence + Verification Steps** - Record reviewer confidence and the next validation task.
5. **Recommendations & Fixes** - Prioritize remediation work with rationale and confidence notes.

### Priority Key
- `High` - Must fix before the next iteration (blocks delivery or alignment).
- `Medium` - Should fix soon to avoid compounding risk.
- `Low` - Optional improvement or polish for later cycles.

## How to Use
1. Copy `promptaudit.md` into your project or agent workspace.
2. Gather prompts, specs, acceptance criteria, and downstream automation context.
3. Fill in each section in order: log issues, explain them, then draft improvements.
4. Share the audit with prompt architects, model operators, or stakeholders and iterate.

## Suggested Workflow
```text
1. Baseline the prompt or specification.
2. Log contradictions and ambiguities in the summary.
3. Capture the context or root causes.
4. Draft clearer language or updated instructions.
5. Assign priorities, confidence, and follow-up owners.
```

## Attribution
Created by SAHS (Stay At Home Sons). Version 1.0 - October 18, 2025.
