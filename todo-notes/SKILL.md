---
name: todo-notes
description: Manage todos tasks list create complete delete. Save notes read search delete. Personal task manager notebook.
---

OUTPUT ONLY ONE JSON LINE. NO <|tool_call|>. NO OTHER TEXT. ONLY ONE OF THESE:

Add todo: {"type":"todo_add","text":"Buy groceries"}
List todos: {"type":"todo_list"}
Complete todo: {"type":"todo_done","id":1}
Delete todo: {"type":"todo_delete","id":1}
Save note: {"type":"note_save","title":"Ideas","content":"My ideas..."}
List notes: {"type":"note_list"}
Read note: {"type":"note_read","id":1}
Search notes: {"type":"note_search","query":"keyword"}
Delete note: {"type":"note_delete","id":1}

STOP. JUST JSON.
