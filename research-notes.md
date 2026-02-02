# Research Notes: Boris Cherny's Workflow Thread on X

Reference: Boris Cherny (@bcherny on X) shared his personal Claude Code setup and team tips (threads from Jan/Feb 2026).

Key takeaways I studied and tried to apply:
- Start complex tasks in **plan mode** first (shift+tab twice or prompt it) — pour energy into planning so implementation is 1-shot.
- Use **subagents** for parallel work: e.g., one for planning, one for reviewing, one for simplifying code after.
- Spin up multiple git worktrees/sessions in parallel for big productivity.
- After mistakes/fixes: Suggest updating rules to prevent repeats.
- Use slash commands (/commit-push-pr, etc.) for repeated workflows.
- Keep context clean, avoid duplication, test small parts often.
- Voice dictation for faster/detailed prompts.
- Team tips: Ghostty terminal, tmux for tabs, statusline showing context usage.

How I applied:
- Added "Always start in plan mode" and "Use subagents when complex" to my rules file.
- Tested: Agent planned better instead of rushing — fewer errors.
- Challenge: Subagents not directly available in VS Code Copilot, but prompted for similar thinking.

Sources:
- Main thread: x.com/bcherny/status/2007179832300581177 (and replies)
- Team tips follow-up threads.
- Summaries on Reddit/YouTube for quick read.
