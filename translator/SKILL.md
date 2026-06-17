---
name: universal-translator
description: Translate text between 100+ languages using Google Translate API. Supports auto-detection of source language. No API key required.
---

# Universal Translator

Translate text between any languages. Auto-detects source language if not specified.

## How to Use

```json
{
  "text": "Hello, how are you?",
  "from": "auto",
  "to": "km"
}
```

Or specify source:
```json
{
  "text": "សួស្តី តើអ្នកសុខសប្បាយទេ?",
  "from": "km",
  "to": "en"
}
```

## Language Codes
- English: en
- Khmer: km
- Thai: th
- Chinese: zh-CN
- Japanese: ja
- Korean: ko
- French: fr
- Spanish: es
- Vietnamese: vi
- And 100+ more...

## Tips
- Use `from: "auto"` when unsure of source language
- The skill preserves formatting and punctuation
- For long texts, break into paragraphs for better results
