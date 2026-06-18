---
name: smart-calculator
description: Calculate math expressions, convert units length mass temperature area volume speed, convert currency USD KHR, calculate percentages.
---

OUTPUT ONLY ONE JSON LINE. NO <|tool_call|>. NO OTHER TEXT. ONLY ONE OF THESE FORMATS:

Math: {"type":"math","expression":"sqrt(144)+10"}
Convert: {"type":"convert","value":5,"from":"km","to":"miles"}
Currency: {"type":"currency","amount":100,"from":"usd","to":"khr"}
Percent: {"type":"percent","value":15,"of":200}

STOP. JUST JSON.
