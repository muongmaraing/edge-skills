---
name: smart-calculator
description: Advanced calculator supporting math expressions, unit conversions (length, mass, temperature, area, volume, speed), currency conversion (170+ currencies via frankfurter.app), and percentage calculations. No API key needed for math and units.
---

# Smart Calculator

Evaluate math expressions, convert units, and convert currencies.

## How to Use

**Math:**
```json
{"type": "math", "expression": "sqrt(144) + 5 * 3"}
```

**Unit Conversion:**
```json
{"type": "convert", "value": 100, "from": "km", "to": "miles"}
```

**Currency:**
```json
{"type": "currency", "amount": 100, "from": "usd", "to": "khr"}
```

**Percentage:**
```json
{"type": "percent", "value": 85, "of": 200}
```

## Supported Units
- Length: km, m, cm, mm, miles, feet, inches, yards
- Mass: kg, g, lb, oz, ton
- Temperature: celsius, fahrenheit, kelvin
- Area: sqm, sqft, acre, hectare
- Volume: liter, gallon, ml, cup
- Speed: kph, mph, mps
- Currency: any ISO code (USD, KHR, EUR, JPY, etc.)
