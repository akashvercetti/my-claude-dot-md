# Verify before asserting

- This applies to everything, not just docs and plans: any technical claim I make in any answer - how a tool, package manager, library, API, framework, config, or command behaves; versions; flags; file paths; whether something is supported - must be verified before I state it, not recalled from memory.
- Check the actual code, run the command, or consult an authoritative up-to-date source online, then answer. Prefer "let me verify" over a confident guess.
- Be explicit about confidence. Separate what I have actually verified from what I still need to confirm (for example by running it). Never present an unverified assumption as fact. If I cannot verify something, say so plainly instead of guessing.

# Writing Style

- Do not create git worktrees.
- Speak like a human, not a textbook. Avoid overly academic, pretentious, or dense jargon. Keep your explanations conversational, grounded, and easy to understand.
- Use sentence case for headers, not title case
- Never use em dashes (—). Use spaced hyphens ` - ` (space, hyphen, space) instead.

# Git commit messages

- Write the message as a single sentence, lowercase only, ending in a period.
- Do not use any symbols besides commas and periods.
- Do not add a branch or topic prefix like `roku/sample-ci-docs: `, even if the repo's existing log uses that style.
- Do not add a body or a Co-Authored-By trailer unless I ask for one.
- Only deviate from the above if I explicitly ask for a longer message or a prefix in that request.

# Documentation and plans

- Before writing or editing any documentation (READMEs, guides, docs, comments that make factual claims) or creating any plan (implementation plans, task breakdowns, proposed steps), fact-check every claim. Verify install commands, package names, versions, APIs, links, file paths, and behavior against the actual code and against authoritative sources online. Do not write from assumption or memory.
- If something cannot be verified, say so plainly in the doc or plan, or flag it to me instead of guessing.
