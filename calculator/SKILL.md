---
name: smart-calculator
description: Calculate math expressions, convert units length mass temperature area volume speed, convert currency USD KHR, calculate percentages.
---

ONE TOOL CALL ONLY. After receiving the result, write your final answer. DO NOT call tool again or output JSON again.

OUTPUT ONLY ONE JSON LINE:
Math: {"type":"math","expression":"sqrt(144)+10"}
Convert: {"type":"convert","value":5,"from":"km","to":"miles"}
Currency: {"type":"currency","amount":100,"from":"usd","to":"khr"}
Percent: {"type":"percent","value":15,"of":200}

NO <|tool_call|>. JUST JSON.
