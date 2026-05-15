# Vedika.io

[![npm version](https://img.shields.io/npm/v/xalen-sdk.svg)](https://www.npmjs.com/package/xalen-sdk)
[![PyPI version](https://img.shields.io/pypi/v/xalen.svg)](https://pypi.org/project/xalen/)

**AI-Powered Astrology API** — The only B2B astrology API with natural language AI queries, voice, and 130+ computation endpoints.

## What We Build

- **200+ AI Models** — LLM, vision, audio, image generation, embeddings via OpenAI-compatible API
- **130+ Astrology Endpoints** — Birth charts, dashas, yogas, doshas, compatibility across Vedic, Western, KP, and Vastu
- **AI Chat Queries** — Ask questions in plain English, Hindi, and 14 Indian languages
- **Vedika Ephemeris Precision** — Accurate planetary calculations with citation-verified accuracy
- **Voice AI** — Multilingual voice astrology across 14 Indian languages

## Quick Links

| Resource | Link |
|----------|------|
| **Website** | [xalen.io](https://xalen.io) |
| **Documentation** | [xalen.io/docs](https://xalen.io/docs) |
| **Playground** | [xalen.io/playground](https://xalen.io/playground) |
| **Pricing** | [xalen.io/pricing](https://xalen.io/pricing) |

## Official SDKs

| Package | Install | Links |
|---------|---------|-------|
| **JavaScript SDK** | `npm install xalen-sdk` | [![npm](https://img.shields.io/npm/v/xalen-sdk.svg)](https://www.npmjs.com/package/xalen-sdk) |
| **Python SDK** | `pip install xalen` | [![PyPI](https://img.shields.io/pypi/v/xalen.svg)](https://pypi.org/project/xalen/) |
| **React Hooks** | `npm install xalen-react` | [![npm](https://img.shields.io/npm/v/xalen-react.svg)](https://www.npmjs.com/package/xalen-react) |
| **MCP Server** | `npx xalen-mcp` | [![npm](https://img.shields.io/npm/v/xalen-mcp.svg)](https://www.npmjs.com/package/xalen-mcp) |

## Quick Start

```python
from xalen import XALEN

client = XALEN(api_key='xln_live_...')
response = client.chat.completions.create(
    model='vedika-standard',
    messages=[{'role': 'user', 'content': 'What is Shakata Yoga?'}]
)
print(response.choices[0].message.content)
```

```javascript
import XALEN from 'xalen-sdk';

const client = new XALEN({ apiKey: 'xln_live_...' });
const response = await client.chat.completions.create({
  model: 'vedika-standard',
  messages: [{ role: 'user', content: 'Analyze planetary transits' }],
});
```

## Support

- **Email:** support@xalen.io
- **Docs:** https://xalen.io/docs

---

**XALEN Technology Pvt Ltd, Pune, India**
