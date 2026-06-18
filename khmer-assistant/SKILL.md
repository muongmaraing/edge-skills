---
name: khmer-assistant
description: search Cambodia news Khmer, translate Khmer English, Cambodian information. For any question in Khmer language or about Cambodia.
---

OUTPUT ONLY ONE JSON LINE. DO NOT USE <|tool_call|>. DO NOT WRITE ANY OTHER TEXT. JUST THIS EXACT FORMAT:

For search: {"action":"search","query":"YOUR QUERY HERE","lang":"km"}
For translate to Khmer: {"action":"translate","text":"TEXT","from":"en","to":"km"}
For translate from Khmer: {"action":"translate","text":"TEXT","from":"km","to":"en"}
For Khmer news: {"action":"news","topic":"កម្ពុជា"}

STOP. NO EXPLANATION. NO <|tool_call|>. ONLY JSON.
