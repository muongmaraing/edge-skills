---
name: weather-forecast
description: Get current weather conditions and forecasts for any city worldwide. Uses Open-Meteo free API — no API key required. Provides temperature, humidity, wind speed, and weather description.
---

# Weather Forecast

Get real-time weather for any city in the world.

## How to Use

```json
{
  "city": "Phnom Penh"
}
```

## Returns
- City, Country
- Weather condition (clear, cloudy, rain, thunderstorm, etc.)
- Current temperature (°C)
- Feels-like temperature
- Humidity percentage
- Wind speed (km/h)

## Tips
- Use city name in English for best results
- Add country code for disambiguation: "Paris, FR" vs "Paris, TX"
- Weather data updates hourly
- No API key, no account, no limits
