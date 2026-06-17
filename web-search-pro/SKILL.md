---
name: web-search-pro
description: Enhanced web search using DuckDuckGo, Wikipedia, and Google News. Use for current events, factual research, definitions, and anything requiring live internet data. No API key needed.
---

# Web Search Pro

Search the live web for any topic. Combines DuckDuckGo Instant Answers, Wikipedia articles, and news headlines in parallel.

## How to Use

Pass a JSON string:
```json
{
  "query": "keyword search query",
  "lang": "en"
}
```

The skill returns:
- DuckDuckGo Instant Answer + related topics + web results
- Wikipedia article intro + infobox (if available)
- News headlines from Google News RSS (if `news: true`)

## Tips

- Use keyword-style queries: "Cambodia economy 2025" not "what is the economy of Cambodia"
- Specify language with `lang`: "en", "fr", "ja", "ko", "zh", "km" (Khmer via Wikipedia)
- Set `news: true` to include current news headlines
- After getting results, synthesize a clear answer with sources cited
