# Vedika.io

[![npm version](https://img.shields.io/npm/v/@vedika-io/sdk.svg)](https://www.npmjs.com/package/@vedika-io/sdk)
[![PyPI version](https://img.shields.io/pypi/v/vedika-sdk.svg)](https://pypi.org/project/vedika-sdk/)

**AI-Powered Vedic Astrology API** - The only B2B astrology API with natural language AI queries.

## What We Build

- **108+ Vedic Astrology Endpoints** - Birth charts, dashas, yogas, doshas, compatibility
- **AI Chatbot Queries** - Ask questions in plain English/Hindi/22 languages
- **Swiss Ephemeris Precision** - Accurate planetary calculations
- **Multi-Agent Intelligence** - Specialized AI agents for different astrological domains

## Quick Links

| Resource | Link |
|----------|------|
| **Website** | [vedika.io](https://vedika.io) |
| **Documentation** | [vedika.io/docs.html](https://vedika.io/docs.html) |
| **API Explorer** | [vedika.io/api-explorer.html](https://vedika.io/api-explorer.html) |
| **Pricing** | [vedika.io/pricing.html](https://vedika.io/pricing.html) |
| **Postman** | [Vedika API Collection](https://www.postman.com/vedikaai/intelligence-platform) |

## Official SDKs & CLI

| Package | Install | Links |
|---------|---------|-------|
| **JavaScript SDK** | `npm install @vedika-io/sdk` | [![npm](https://img.shields.io/npm/v/@vedika-io/sdk.svg)](https://www.npmjs.com/package/@vedika-io/sdk) |
| **Python SDK** | `pip install vedika-sdk` | [![PyPI](https://img.shields.io/pypi/v/vedika-sdk.svg)](https://pypi.org/project/vedika-sdk/) |
| **CLI Tool** | `npx @vedika-io/cli` | [![npm](https://img.shields.io/npm/v/@vedika-io/cli.svg)](https://www.npmjs.com/package/@vedika-io/cli) |

## Quick Start

```bash
# CLI - Initialize a new project
npx @vedika-io/cli init

# CLI - Test connection (sandbox)
npx @vedika-io/cli test --sandbox

# CLI - Generate birth chart
npx @vedika-io/cli generate chart

# Direct API (no signup needed)
curl https://api.vedika.io/sandbox/horoscope/daily?sign=aries
```

## SDK Usage

**JavaScript/TypeScript:**
```javascript
import { VedikaClient } from '@vedika-io/sdk';

const client = new VedikaClient({ apiKey: 'vk_live_...' });
const response = await client.askQuestion({
  question: 'What are my career prospects?',
  birthDetails: { datetime: '1990-06-15T14:30:00', latitude: 28.6139, longitude: 77.2090 }
});
```

**Python:**
```python
from vedika import VedikaClient

client = VedikaClient(api_key='vk_live_...')
response = client.ask_question(
    question='What are my career prospects?',
    birth_details={'datetime': '1990-06-15T14:30:00', 'latitude': 28.6139, 'longitude': 77.2090}
)
```

## Connect With Us

[![Twitter](https://img.shields.io/badge/Twitter-@VedikaAPI-1DA1F2?style=flat&logo=twitter)](https://x.com/VedikaAPI)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vedika_API-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/company/vedika-api/)

## Support

- **Email:** support@vedika.io
- **Docs:** https://vedika.io/docs.html

---

**Built with love in India**
