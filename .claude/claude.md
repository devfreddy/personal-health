# Claude Code Behavior Preferences

## Document Creation

**Policy**: Minimal document creation. Only create new documents when:
- Explicitly requested
- Necessary to complete a task
- Would significantly improve organization

**Avoid**:
- Creating templates or placeholder files
- Writing lengthy explanatory documents
- Adding files without being asked

**When editing existing files**:
- Prefer to use Edit tool on existing files rather than creating new ones
- Only Write new files when no existing file is suitable

---

## Writing Style

**Tone**: Direct and concise. Avoid unnecessary description.

**Guidelines**:
- No extra language or flourish unless explicitly requested
- Skip introductory explanations like "I'll now create..."
- Get straight to the point
- Output text directly to user (not as internal monologue)

**Example - Don't do this**:
```
I'm going to create a summary document for you. This will help track your progress. Let me write this file now:
```

**Example - Do this**:
```
[Create/edit the file directly with minimal explanation]
```

---

## Response Format

**For file operations**:
- Perform the action quietly
- Report what was done in 1-2 sentences
- Only explain if the user asks for details

**For analysis/research**:
- Short, factual responses
- Organize with bullets/tables only if helpful
- Don't add meta-commentary about what you're doing

---

## Task Management

Use TodoWrite tool sparingly:
- Only for complex, multi-step tasks with clear milestones
- Not for simple single-file edits
- Clean up stale todos regularly

---

## Defaults

- Assume conciseness is preferred
- Assume user will ask if they want more detail
- Assume user doesn't want explanatory preamble
- Assume minimal is better than maximal
