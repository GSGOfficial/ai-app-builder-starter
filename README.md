# AI App Builder Blueprint — Starter Project

This is your starting point for the **AI App Builder Blueprint** course.
You will turn your own idea into a working app by leading a team of AIs.

## Your Team
| Who | Job |
|---|---|
| You | Project Manager — test every wave, keep the files up to date, make the final call |
| ChatGPT (Codex in VS Code) | Planner + Approver — writes plans, gives Go / No-Go |
| Claude (Claude Code in VS Code) | Builder — builds each wave and writes an audit |
| Grok (optional) | Planner in the three-AI process |

## Start Here
This repository is **read-only**. You clone it to get started, but you never save your work back to it.
Your app gets its own private repository on your GitHub account.

1. In VS Code, open a new window. Ask Claude:
   *"Clone https://github.com/GSGOfficial/ai-app-builder-starter.git into a new folder called [your-app-name] and open it."*
2. Then ask Claude:
   *"This project was cloned from a course starter. Create a new private GitHub repository on my account called [your-app-name], connect this project to it instead of the starter, and push. Explain each step first."*
3. Check github.com. Your new private repository should be there, with all the starter files.
4. Follow Module 3 of the course to fill in your files.

## What's Inside
```
CLAUDE.md                  Rules Claude reads automatically
AGENTS.md                  Rules ChatGPT (Codex) reads automatically
.gitignore                 Keeps your secret keys off GitHub
docs/
  SPEC.md                  The approved plan for your app
  PROJECT_TRACKER.md       Waves, status, and every Go / No-Go
  TESTING.md               Your test steps and results
  APP_FUNCTIONS.md         Everything the app does right now
  HANDOFF.md               The note passed to the next team member
  APP_FUNCTIONS_HTML_PROMPT.md   Optional: make a browser-friendly page
  waves/
    WAVE_PLAN.md           Copy this for each wave's plan
    WAVE_AUDIT.md          Copy this for each wave's audit
```

## The Golden Rules
- Only Claude builds. ChatGPT plans and approves.
- No wave gets a Go until **you** test it by hand.
- Read the docs files at the start of every session. Update them at the end.
- Secret keys go in `.env.local` only. Never in code, docs, or chat.
