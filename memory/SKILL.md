---
name: persistent-memory
description: Save, recall, and manage information across chat sessions. Use this for remembering user preferences, important facts, project details, and anything the user wants to recall later. Persistent storage via localStorage.
---

# Persistent Memory

You have access to permanent memory that survives across sessions. Use it to remember user information, preferences, and important facts.

## How to Use

Pass a JSON string with `action` and relevant parameters:

**Save:**
```json
{"action": "save", "key": "user_name", "value": "Maraing"}
```

**Recall one:**
```json
{"action": "recall", "key": "user_name"}
```

**Recall all:**
```json
{"action": "recall_all"}
```

**Delete:**
```json
{"action": "delete", "key": "old_fact"}
```

**Search:**
```json
{"action": "search", "query": "keyword"}
```

## When to Use Memory

- User tells you their name, preferences, or important context → SAVE IT
- User asks "remember this" → SAVE IT
- Starting a new conversation, recall past context → RECALL ALL
- User corrects you → SAVE the correction

Be proactive! If the user shares something that will matter later, save it without being asked.
