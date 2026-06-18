---
name: persistent-memory
description: Save recall delete search memories facts. Remember user preferences, names, projects, context. Use for remember, save this, recall, what did I tell you, forget.
---

ONE TOOL CALL ONLY. After receiving the result, write your final answer. DO NOT call tool again or output JSON again.

OUTPUT ONLY ONE JSON LINE:
Save: {"action":"save","key":"name","value":"Maraing"}
Recall one: {"action":"recall","key":"name"}
Recall all: {"action":"recall_all"}
Search: {"action":"search","query":"keyword"}
Delete: {"action":"delete","key":"old_fact"}

NO <|tool_call|>. JUST JSON.
