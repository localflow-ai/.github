# LocalFlow — Metadata-first AI

[![npm](https://img.shields.io/npm/v/@localflow/core)](https://www.npmjs.com/package/@localflow/core)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/localflow-ai/localflow-core/blob/main/LICENSE)
[![Live demo](https://img.shields.io/badge/demo-live-brightgreen)](https://apps.localflow.fr/demo/)

> **The LLM sees only your data's structure — never its values.**

In **metadata-first AI**, the model receives only metadata — column names, statistical samples, document structure. It acts as a one-time code generator: the analysis code it writes runs locally in a sandbox on your full dataset. Your actual data never crosses the inference boundary.

This unlocks **"Talk to your Data"** on sensitive datasets, large-scale analytical pipelines, and document intelligence — without privacy trade-offs, without hallucinated results, and at a fraction of the token cost of classical AI agents.

| | Classical cloud AI | Local-model AI | Metadata-first AI |
|---|---|---|---|
| Raw data stays local | ❌ | ✅ | ✅ |
| Uses best-in-class models | ✅ | Limited | ✅ |
| Results are deterministic | ❌ | ❌ | ✅ |
| Re-runs without AI tokens | ❌ | ❌ | ✅ |

---

## Projects

### [localflow-core](https://github.com/localflow-ai/localflow-core)
The framework — embed metadata-first AI in any web app in minutes.
- `LocalAssistant` — natural language interface over your datasets
- `LocalProxy` — browser-side proxy for zero-config demos and development
- `ProxyClient` — connects to a self-hosted proxy for production use

```bash
npm install @localflow/core
```

---

### [localflow-examples](https://github.com/localflow-ai/localflow-examples)
Ready-to-run examples showing metadata-first AI in action — React + TypeScript and plain JavaScript, both built on Vite.

🚀 [Live demo](https://apps.localflow.fr/demo/) — load a CSV or Excel file and start asking questions. Your data never leaves the browser.

---

### [localflow-proxy](https://github.com/localflow-ai/localflow-proxy)
The production gateway — a zero-trust edge service that sits between the AI sandbox and the outside world. Every outbound API call is explicitly whitelisted, authenticated, and audited. Manages LLM keys server-side, enforces rate limits, and supports PDF extraction, CRM connectors, and custom API integrations.

---

## Learn more

- 🌐 [localflow.fr](https://localflow.fr) — website
- 📄 [White paper](https://localflow.fr/LocalFlow%20-%20white%20paper%20-%20en.pdf) — deep dive into the metadata-first AI paradigm
- 💬 [contact@localflow.fr](mailto:contact@localflow.fr)
