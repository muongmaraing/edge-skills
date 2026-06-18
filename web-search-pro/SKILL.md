---
name: web-search-pro
description: Enhanced web search DuckDuckGo Wikipedia Google News. Search for current events, facts, information, news. Find anything on the internet.
---

OUTPUT ONLY ONE JSON LINE. NO <|tool_call|>. NO OTHER TEXT. ONLY THIS FORMAT:

{"query":"YOUR SEARCH QUERY","lang":"en","news":true}

Use lang="km" for Khmer searches. Set news:true to include Google News headlines.

STOP. JUST JSON.
