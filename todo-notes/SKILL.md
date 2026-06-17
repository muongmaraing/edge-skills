---
name: todo-notes
description: Personal task manager and notebook. Create, list, complete, and delete todos. Save and search notes. All data stored persistently on-device via localStorage.
---

# Todo & Notes Manager

Manage tasks and notes with persistent on-device storage.

## Todo Commands

**Add todo:**
```json
{"type": "todo_add", "text": "Buy groceries"}
```

**List todos:**
```json
{"type": "todo_list"}
```

**Complete todo:**
```json
{"type": "todo_done", "id": 1}
```

**Delete todo:**
```json
{"type": "todo_delete", "id": 1}
```

## Notes Commands

**Save note:**
```json
{"type": "note_save", "title": "Meeting Notes", "content": "Discussed Q3 budget..."}
```

**List all notes:**
```json
{"type": "note_list"}
```

**Read a note:**
```json
{"type": "note_read", "id": 1}
```

**Search notes:**
```json
{"type": "note_search", "query": "budget"}
```

**Delete note:**
```json
{"type": "note_delete", "id": 1}
```

## Tips
- Todos have IDs — use them to mark done or delete
- Notes are stored with timestamps
- All data persists across app restarts
- Use note_search to find old notes by keyword
