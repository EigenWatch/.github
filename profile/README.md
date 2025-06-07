# EigenWatch 🛡️📊📡

*Real-Time Risk Intelligence for Ethereum's Restaking Ecosystem*

---

## 🧠 What is EigenWatch?

**EigenWatch** is an open-source telemetry, alerting, and oracle infrastructure purpose-built for Ethereum's **EigenLayer** ecosystem. Our mission is to provide restaking participants—validators, LRTs, AVSs, and insurance protocols—with **transparent, real-time visibility** into slashing risk, validator behavior, and correlated exposures.

We are building the **first modular risk scoring oracle and reputation index** for restaking, making systemic risk intelligible and actionable.

> Read our [Whitepaper](https://www.notion.so/EigenWatch-WhitePaper-2046775048bc8035b227cdae8c6f6f43) for an in-depth technical overview.

---

## 🏗️ Organizational Structure

This GitHub organization hosts several focused repositories, each representing a key component of the EigenWatch system:

| Repository | Description |
|-----------|-------------|
| [`smartcontract`](https://github.com/EigenWatch/smartcontract) | Solidity smart contracts for oracle publishing, reputation indexing, and AVS integration. Tested using TypeScript-based tooling. |
| [`website`](https://github.com/EigenWatch/website) | The official company website. Built with Next.js and TypeScript. |
| [`dapp`](https://github.com/EigenWatch/dapp) | The main user-facing dashboard for exploring validator risk, reputation, and telemetry data. Built with Next.js and Tailwind CSS. |
| [`backend`](https://github.com/EigenWatch/backend) | NestJS backend service for data ingestion, scoring, webhook delivery, and API exposure. Acts as the core analytics and orchestration layer. |

> More repositories will be added as the project evolves (e.g., SDKs, subgraphs, AVS-specific adapters).

---

## 🚀 Vision

Restaking unlocks capital efficiency but also introduces opaque risks. We believe that **risk-aware restaking** is critical for Ethereum's long-term decentralization and security.

### Our Goals:

- Deliver **slashing alert APIs** and onchain feeds
- Maintain a **validator reputation index**
- Provide a **risk scoring oracle** for use in DeFi, staking, and insurance
- Enable **ecosystem-wide integration** with LRTs, AVSs, and risk tools

---

## 📡 Core Components

- **Risk Scoring Oracle**: Quantifies validator risk based on performance, uptime, AVS behavior, and slashing history.
- **Slashing Alerts Feed**: Real-time webhook + oracle notification system for validator misbehavior.
- **Reputation Index**: A long-term, data-driven measure of validator reliability and exposure.
- **Telemetry Dashboard**: Frontend for restakers and protocols to interact with risk data.

---

## 🗺️ Roadmap Snapshot (2025–2026)

| Timeline | Milestones |
|----------|------------|
| **Q3 2025** | MVP Dashboard, Initial Risk Engine |
| **Q4 2025** | Oracle Launch (Top 100 Validators), Slashing Alerts API |
| **Q1 2026** | Reputation Index Live, Ecosystem Partnerships |
| **Q2 2026** | Insurance Experiments, Ecosystem-wide API Access |

---

## 💡 Why EigenWatch?

- 🛠️ **Modular**: APIs and oracles that integrate seamlessly into LRTs, AVSs, and staking platforms.
- 📊 **Data-Rich**: Pulls from AVS telemetry, Ethereum, and EigenLayer participation.
- 🔗 **Onchain + Offchain**: Oracle-ready feeds + APIs for offchain consumers.
- 🤝 **Ecosystem Native**: Built exclusively for Ethereum restaking and EigenLayer participants.
- 🧩 **Composable**: Enables downstream tooling like insurance underwriting, AVS scoring, and staking strategies.

---

## 📬 Get Involved

We welcome contributors from the Ethereum, DeFi, and validator communities.

- Check out [`CONTRIBUTING.md`](https://github.com/EigenWatch/.github/blob/main/CONTRIBUTING.md)
- Reach us via [team@eigenwatch.xyz](mailto:team@eigenwatch.xyz)
- Follow us on [Twitter @eigenwatch](https://twitter.com/eigenwatch)

---

## 📄 License

MIT License © EigenWatch Contributors

---

## 🔗 Resources

- 📜 [Whitepaper](https://www.notion.so/EigenWatch-WhitePaper-2046775048bc8035b227cdae8c6f6f43)
- 🧰 [GitHub Repos](https://github.com/EigenWatch)

> _Transparency is the foundation of trust. At EigenWatch, we make restaking risk measurable and open._
