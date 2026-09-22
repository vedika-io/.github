# Vedika

**Astrology intelligence infrastructure for developers and businesses.**

Vedika provides structured astrology calculations, grounded AI interpretation, and developer tooling through a dedicated API and SDKs. Vedika is a product of **Xalen Technology Pvt Ltd**.

## Start building

| Resource | Link |
| --- | --- |
| Website | [vedika.io](https://vedika.io) |
| Documentation | [vedika.io/docs](https://vedika.io/docs) |
| API reference | [api.vedika.io/openapi.json](https://api.vedika.io/openapi.json) |
| SDKs | [vedika.io/sdks](https://vedika.io/sdks) |
| Sandbox | [vedika.io/sandbox](https://vedika.io/sandbox) |
| Status | [vedika.io/status](https://vedika.io/status) |
| Support and feature requests | [vedika-community](https://github.com/vedika-io/vedika-community) |

## Official developer tools

| Tool | Install or source |
| --- | --- |
| JavaScript / TypeScript | [`npm install @vedika-io/sdk`](https://www.npmjs.com/package/@vedika-io/sdk) |
| Python | [`pip install vedika-sdk`](https://pypi.org/project/vedika-sdk/) |
| React | [`npm install @vedika-io/react`](https://www.npmjs.com/package/@vedika-io/react) |
| MCP server | [`npx @vedika-io/mcp-server`](https://www.npmjs.com/package/@vedika-io/mcp-server) |
| Android | [`vedika-sdk-android`](https://github.com/vedika-io/vedika-sdk-android) |
| Swift | [`vedika-sdk-swift`](https://github.com/vedika-io/vedika-sdk-swift) |

### JavaScript

```javascript
import { VedikaClient } from '@vedika-io/sdk';

const vedika = new VedikaClient({
  apiKey: process.env.VEDIKA_API_KEY,
});
```

### Python

```python
import os
from vedika import VedikaClient

vedika = VedikaClient(api_key=os.environ["VEDIKA_API_KEY"])
```

Keep live keys on the server. Do not embed them in browser, mobile, theme, or public repository code.

## Product boundaries

- **Vedika** is the astrology intelligence API. Vedika integrations use `api.vedika.io`, Vedika SDKs, and `vk_…` keys.
- **XALEN Ephemeris** is the open-source astronomical computation engine used by Vedika. Its source is available at [`xalen-ephemeris`](https://github.com/vedika-io/xalen-ephemeris).
- **Xalen** is the parent company's broader AI platform. It has a separate API, account, SDK, documentation, and key namespace at [xalen.io](https://xalen.io).

Using XALEN Ephemeris or being owned by Xalen Technology does not make the Vedika API and Xalen API interchangeable.

## Community and support

Use [`vedika-community`](https://github.com/vedika-io/vedika-community) for public bug reports, documentation feedback, integration questions, and feature requests.

For account, billing, or private security matters, use [Vedika support](https://vedika.io/contact) instead of posting sensitive information publicly.

---

Vedika is developed and operated by **Xalen Technology Pvt Ltd**.
