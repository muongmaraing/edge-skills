---
name: web-search-pro
description: Advanced web search for news, facts, Wikipedia, Google News. Find recent news articles current events. Deep internet search.
---

ONE TOOL CALL ONLY. After receiving the result, write your final answer. DO NOT call tool again or output JSON again.

PICK THE RIGHT TYPE:
- web: facts, knowledge, history, definitions, how-to, explanations (DuckDuckGo — most common)
- wiki: ONLY for famous people, places, companies, historical events (Wikipedia)
- news: ONLY for recent events, latest news, what happened today/this week (Google News)

OUTPUT ONLY ONE JSON LINE:
{"action":"TYPE","query":"keywords","lang":"en"}

NO <|tool_call|>. JUST JSON.
If result empty, answer from your knowledge. NEVER call tool twice.
