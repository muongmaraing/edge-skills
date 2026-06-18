---
name: persistent-memory
description: Save recall delete search memories facts. Remember user preferences, names, projects, context. Use for remember, save this, recall, what did I tell you, forget.
---

OUTPUT ONLY ONE JSON LINE. NO <|tool_call|>. NO OTHER TEXT. ONLY ONE OF THESE:

Save: {"action":"save","key":"name","value":"Maraing"}
Recall one: {"action":"recall","key":"name"}
Recall all: {"action":"recall_all"}
Search: {"action":"search","query":"keyword"}
Delete: {"action":"delete","key":"old_fact"}

STOP. JUST JSON.
