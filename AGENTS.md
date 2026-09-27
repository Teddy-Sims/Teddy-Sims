# AI conventions

## About this repository
This is Teddy Sims’s public professional portfolio for operations leadership, business analytics, strategy, supply chain, and organizational transformation.
Canonical file: AGENTS.md. CLAUDE.md points here.

## Where things are
- capabilities/<capability>/  a capability, with its spec and model
- docs/briefs/          written BEFORE work: scope + hypothesis
- docs/decisions/       written AFTER work: recommendations
- analysis/             findings and figures
- data/                 sourced inputs, with provenance

## Naming
- The directory matters most. A file in the wrong folder may not be found
  at all. If you are not certain which folder a file belongs in, ask me
  before you write it — do not choose for me.
- Graded files use the exact filename the stage brief gives — lowercase,
  hyphens, no spaces. Some courses date-stamp (YYYY-MM-DD-lastname-slug.md);
  the stage page says so when they do.
- Slugs name the engagement, never the week, the course, or the assignment
  number.
- Never invent a path or a filename. I will give you the exact one.

## How I work
- Explain concepts fully, connect them to the business decision, and walk through a worked example when numbers or formulas are involved.
- Critique my reasoning directly. I would rather be corrected than agreed with.
- Help me connect high-level strategy to frontline execution, people, process, safety, and financial impact.
- Show assumptions, formulas, sources, and limitations clearly enough that I can verify and explain the work myself.
- When you are uncertain, say so and tell me what information would resolve it.

## What you may and may not draft
- You MAY explain, critique, debug, quiz me, improve formatting, and draft mechanical repository files.
- You MAY review my drafts and identify weak claims, missing evidence, alternative explanations, and unsupported assumptions.
- You MAY NOT write my briefs, analyses, memos, or reflections. I draft those first; you may critique them afterward.
- Every statistic, figure, date, job title, credential, and factual claim you give me is a draft until I verify it against a source.

## Verification before committing
- Read every line of every generated file before recommending a commit.
- Search for unfinished placeholders, bracketed template text, TODO markers, invented facts, and broken or case-mismatched links.
- Verify that every linked file exists at the exact path and capitalization used in the link.
- Confirm that every directory contains a tracked file because Git does not preserve empty folders.
- For spreadsheets and financial models, verify source inputs, formulas, units, signs, time periods, scenario assumptions, and outputs before using a result in a recommendation.
- For public-facing files, confirm that no private employer, employee, client, customer, military, or classmate information appears anywhere in the file or its history.

## Documentation
When work changes, update the document that describes it in the same commit.
A capability’s README names the engagements that exercised it — keep that current.

## Scope
Do the work I asked for. If you notice something worth doing that I did not ask for, tell me instead of doing it.

## Commits
Use descriptive messages that say what changed and why. Never use vague messages such as “update” or “stuff.”

## Prompt log
At the end of every session that changed a file, append one entry to
prompt-log.md: the date, what I asked, what you produced, what was wrong and how
it was caught. Never backfill earlier sessions and never edit a past entry.

## Never include
- Credentials, passwords, API keys, access tokens, tax identifiers, banking information, or private contact information.
- McCabe employee or applicant records, names tied to personnel files, Social Security numbers, birth dates, addresses, benefits or life-insurance information, termination records, training records, workers’ compensation details, or return-to-work information.
- Mobile detailing customer names, phone numbers, addresses, vehicle identifiers, payment details, private complaints, schedules, access instructions, or photographs that identify a customer or location.
- Financial-services client names, account information, portfolio details, financial plans, or personally identifiable financial information.
- Military personnel records, family information, government asset details, readiness data, operational information, or controlled material.
- Confidential employer documents, vendor proposals, union information, nonpublic business data, licensed course materials, copyrighted textbooks, or information covered by an agreement.
- If I paste anything that fits these descriptions, stop and tell me rather than placing it in the repository or another model.

## Mistakes to avoid
- Never commit bracketed placeholders, template slots, TODO markers, or unverified substitute text to a public file.
- Check filename capitalization and every internal link before committing; GitHub paths are case-sensitive.
- Do not invent missing dates, employers, schools, credentials, software skills, or performance results. Ask me or remove the field.
- Do not assume a folder exists in Git just because it exists locally; it needs a tracked file.
- Treat an AI-generated file as unfinished until a human verification pass is complete.

