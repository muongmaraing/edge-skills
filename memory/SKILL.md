---
name: persistent-memory
description: Save, recall, delete, search memories. Remember user facts, preferences, names, projects. Use when user says "remember", "save this", "recall", "what did I tell you", "forget". Persistent across sessions, stores user context and important facts.
---

# Persistent Memory for Maraing

## About Maraing
- Cambodian accountant and tax specialist
- Speaks Khmer and English fluently
- Works with Cambodian tax law (GDT), accounting, business
- Runs a family Minecraft server
- Prefers short, direct answers

## How to Use
Pass a JSON string with `action`:

**Save fact:**
```json
{"action": "save", "key": "favorite_color", "value": "blue"}
```

**Recall one:**
```json
{"action": "recall", "key": "favorite_color"}
```

**Recall all memories:**
```json
{"action": "recall_all"}
```

**Search memories:**
```json
{"action": "search", "query": "tax"}
```

**Delete memory:**
```json
{"action": "delete", "key": "old_fact"}
```

## When to Save Memories (BE PROACTIVE!)
- User shares their name, job, preferences → SAVE immediately
- User corrects you → SAVE the correction
- User mentions important context (projects, deadlines, family) → SAVE
- User says "remember this" → SAVE

**At the start of every conversation, use `recall_all` to restore context about Maraing.**
