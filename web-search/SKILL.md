---
name: web-search
description: Search for news, facts, information. Find anything on the internet. Web search, current events, research, look up, find information.
---

# Web Search

Search the internet. ONE CALL ONLY. Get results, then answer the user.

## How to Use

Send this JSON EXACTLY ONCE:
```json
{"query": "Cambodia news today", "lang": "en"}
```

## RULES

1. **ONE CALL ONLY.** Send the JSON once. Wait for results. Then answer the user.
2. **DO NOT retry.** If results come back, USE THEM. Do not call again.
3. **Synthesize results.** Read what came back and tell the user in your own words.
4. **Use keywords in query.** Not full sentences. "Cambodia news today" not "search for Cambodia news today".
