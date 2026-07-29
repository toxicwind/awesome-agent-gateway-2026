# 🚀 Awesome Agent Gateway 2026

> A curated, opinionated list of agent gateway frameworks, SDKs, and tools for
> building production-ready multi-agent systems in 2026.
>
> **Last Updated**: July 2026 | **Python**: 3.12+ | **License**: CC0-1.0

<p align="center">
  <img src="assets/banner.png" alt="Awesome Agent Gateway 2026" width="800">
</p>

<p align="center">
  <a href="#frameworks">Frameworks</a> •
  <a href="#sdks">SDKs</a> •
  <a href="#gateways">Gateways</a> •
  <a href="#tools">Tools</a> •
  <a href="#resources">Resources</a>
</p>

---

## ✨ Why This List?

In 2026, the agent ecosystem has exploded. Every major AI provider now offers
some form of agent runtime, gateway, or orchestration layer. This list cuts
through the noise to highlight tools that are:

- **Production-ready** — battle-tested in real workloads
- **Actively maintained** — commits within the last 3 months
- **Well-documented** — comprehensive docs and examples
- **Open ecosystem** — not locked to a single provider

---

## 🏗️ Frameworks

### Multi-Agent Orchestration

| Framework | Lang | Stars | Description |
|-----------|------|-------|-------------|
| [AgenticX](https://github.com/DemonDamon/AgenticX) | Python | 15k+ | Unified multi-agent platform with Meta-Agent orchestration, 15+ LLM providers, MCP Hub |
| [AutoGen](https://github.com/microsoft/autogen) | Python | 40k+ | Microsoft's multi-agent conversation framework |
| [CrewAI](https://github.com/joaomdmoura/crewai) | Python | 25k+ | Framework for orchestrating AI agent teams |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Python | 20k+ | Stateful, multi-actor applications from LangChain |
| [PydanticAI](https://github.com/pydantic/pydantic-ai) | Python | 12k+ | Agent framework built on Pydantic |

### Agent Gateways

| Gateway | Lang | Protocols | Description |
|---------|------|-----------|-------------|
| [agent-gateway-hub](https://github.com/Rakshit64w43/agent-gateway-hub) | Python/Node | Slack, Telegram, Discord, DingTalk, Feishu | Universal AI Agent Gateway with session persistence |
| [SwarmClaw](https://github.com/ai-for-developers/awesome-ai-coding-tools) | Python | MCP, WebSocket, REST | Self-hosted multi-agent runtime with 23+ LLM providers |
| [AgentsMesh](https://github.com/ai-for-developers/awesome-ai-coding-tools) | Python | GitHub, GitLab, Gitee | Self-hostable AI Agent Workforce Platform |

---

## 📦 SDKs

### Official SDKs

| Provider | SDK | Lang | Install |
|----------|-----|------|---------|
| OpenAI | [openai-python](https://github.com/openai/openai-python) | Python | `pip install openai` |
| Anthropic | [anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python) | Python | `pip install anthropic` |
| Google | [google-genai](https://github.com/googleapis/python-genai) | Python | `pip install google-genai` |
| Moonshot AI | [kimi-agent-sdk](https://github.com/MoonshotAI/kimi-agent-sdk) | Python/Go/Node | `pip install kimi-agent-sdk` |

### Community SDKs

| SDK | Lang | Features |
|-----|------|----------|
| [OpenAI Codex CLI](https://github.com/openai/codex) | Python | Terminal coding agent with sandboxed execution |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Python | Google's terminal coding agent |
| [OpenCode](https://github.com/opencode-ai/opencode) | Python | 75+ providers, multi-session, privacy-first |

---

## 🌐 Gateways

### IM Platform Connectors

| Platform | Library | Protocol |
|----------|---------|----------|
| Slack | [slack-sdk](https://github.com/slackapi/python-slack-sdk) | WebSocket/REST |
| Discord | [discord.py](https://github.com/Rapptz/discord.py) | Gateway |
| Telegram | [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) | Bot API |
| Feishu (Lark) | [lark-openapi](https://github.com/larksuite/oapi-sdk-python) | OpenAPI |
| WeChat Work | [wechatpy](https://github.com/wechatpy/wechatpy) | CorpAPI |
| DingTalk | [dingtalk-python](https://github.com/zabbix-book/dingtalk-alert) | OpenAPI |

### Message Brokers

| Broker | Library | Pattern |
|--------|---------|---------|
| Redis | [redis-py](https://github.com/redis/redis-py) | Pub/Sub |
| RabbitMQ | [pika](https://github.com/pika/pika) | AMQP |
| Kafka | [kafka-python](https://github.com/dpkp/kafka-python) | Streaming |
| NATS | [nats-py](https://github.com/nats-io/nats.py) | Pub/Sub |

---

## 🛠️ Tools

### Development & Debugging

| Tool | Purpose |
|------|---------|
| [LangSmith](https://smith.langchain.com) | LLM observability and evaluation |
| [Promptfoo](https://github.com/promptfoo/promptfoo) | Open-source LLM testing |
| [Arize Phoenix](https://github.com/arize-ai/phoenix) | ML observability |
| [Braintrust](https://www.braintrust.dev) | LLM evaluation and monitoring |

### Deployment

| Tool | Description |
|------|-------------|
| [Docker](https://docker.com) | Containerization |
| [Kubernetes](https://kubernetes.io) | Container orchestration |
| [Helm](https://helm.sh) | K8s package manager |
| [Skaffold](https://skaffold.dev) | Continuous development |

---

## 📚 Resources

### Learning

- [Building LLM Apps](https://www.oreilly.com/library/view/building-llm-apps/9781098157292/) — O'Reilly, 2026
- [Multi-Agent Systems](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems/) — DeepLearning.AI
- [MCP Specification](https://modelcontextprotocol.io) — Model Context Protocol

### Communities

- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) — Local model discussion
- [Hugging Face Agents](https://huggingface.co/agents) — Agent models and datasets
- [LangChain Discord](https://discord.gg/langchain) — Framework community

---

## 🏆 Star History

<p align="center">
  <img src="assets/star-history.png" alt="Star History" width="600">
</p>

---

## 🤝 Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

1. Fork the repository
2. Create a feature branch
3. Add your tool with a concise description
4. Submit a PR

### Contribution Guidelines

- Tools must be actively maintained (commits within 3 months)
- Include Python version compatibility
- Prefer open-source with permissive licenses
- No affiliate links or paid placement

---

## 📜 License

This list is licensed under [CC0-1.0](LICENSE).

> To the extent possible under law, the contributors have waived all copyright
> and related or neighboring rights to this work.

---

<p align="center">
  <sub>Built with ❤️ by the agent gateway community · 2026</sub>
</p>