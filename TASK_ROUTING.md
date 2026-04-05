# TASK_ROUTING.md

Routing Order:

1. Gemma
   - summaries
   - formatting
   - quick drafts
   - cleanup

2. Q (Qwen)
   - reasoning
   - planning
   - coding support
   - structured execution

3. Codex
   - complex debugging
   - architecture decisions
   - final high-quality output

Fallback Rules:
- If Codex unavailable → use Q
- If Q unavailable/slow → use Gemma
- Never block progress
- Always complete task with available model