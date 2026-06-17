---
name: weather-forecast
description: Get current weather conditions for any city worldwide. Automatically triggers when user asks about weather, temperature, rain, forecast, or climate. Uses Open-Meteo free API — no API key required.
---

# Weather Forecast

⚡ You have real-time weather access. When a user asks about weather, USE THIS TOOL. Do NOT say "I cannot access weather data."

## How to Use

Send this JSON:
```json
{"city": "Phnom Penh"}
```

Just the city name — nothing else. The system will return temperature, condition, humidity, and wind speed.

## Trigger Words

Use this tool when user mentions ANY of these:
- "weather", "temperature", "how hot", "how cold"
- "is it raining", "rain", "sunny", "cloudy"
- "forecast", "climate", "umbrella"
- "what's it like outside", "how's the weather"

## Examples

| User says | You send |
|-----------|----------|
| "What's the weather in Phnom Penh today?" | `{"city": "Phnom Penh"}` |
| "Is it raining in Siem Reap?" | `{"city": "Siem Reap"}` |
| "How hot is it in Bangkok?" | `{"city": "Bangkok"}` |
| "Temperature in Tokyo?" | `{"city": "Tokyo"}` |

## IMPORTANT

- Extract the city name from the user's message. Do NOT ask them to repeat it.
- If user says "weather in Phnom Penh" — city is "Phnom Penh". Just send it.
- After getting results, tell the user naturally: "It's 32°C and partly cloudy in Phnom Penh."
