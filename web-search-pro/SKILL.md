---
name: web-search-pro
description: Advanced web search for news, facts, Wikipedia, Google News. Find recent news articles current events. Deep internet search.
---

DO NOT REPEAT. SEND ONE JSON THEN STOP. NEVER SEND A SECOND JSON.

PICK ONE ACTION:
- web: facts, knowledge, history, definitions, how-to (most common - ALWAYS use this unless user asks for news or wiki)
- wiki: ONLY when user says "wikipedia" or "who is" a famous person/place
- news: ONLY when user asks "latest news", "today", "recent", "current events"

FORMAT (pick one):
{"action":"web","query":"your keywords","lang":"en"}
{"action":"wiki","query":"topic","lang":"en"}
{"action":"news","query":"topic"}

STOP. NO <|tool_call|>. ONE JSON ONLY. AFTER JSON, WRITE ANSWER. NEVER JSON AGAIN.
