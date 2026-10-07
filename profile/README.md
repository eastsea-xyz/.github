# EastSea · 동해

**A blockchain your Mac runs and checks itself.**
Your wallet key stays in the Mac's Secure Enclave, and Touch ID approves every payment. There is no seed phrase. The Mac checks each balance itself instead of trusting a server.

> [!IMPORTANT]
> **Mainnet has not launched.** The network running today is the public testnet (chain 7780). Test DBLN has no value and does not carry over. There is no token sale, and nothing here promises a price or a return. The software is provided **AS IS** and has had no independent security audit. See the [Disclaimer](https://github.com/eastsea-xyz/eastsea/blob/main/DISCLAIMER.md).

## Get started

- **Mac app:** download the [latest EastSea release](https://github.com/eastsea-xyz/eastsea/releases/latest) (Apple silicon, notarized) and drag it to Applications. Updates arrive automatically.
- **Run a node:** with the switch on, the app also runs a node that verifies every block on your Mac. Macs that stay online can become voting validators.
- **For AI agents:** `aether-agent` gives Claude Code, Codex or any MCP client a wallet. The account contract enforces the spending limits on chain, and only you can change them, with Touch ID.

## Repositories

| | |
|---|---|
| [**eastsea**](https://github.com/eastsea-xyz/eastsea) | Node, wallet apps (macOS / iOS), browser extension, agent tools, specs and audits |
| [**eastsea-toolbox**](https://github.com/eastsea-xyz/eastsea-toolbox) | Smart contract examples with tests, benchmarks and front-end templates. Published AS IS: anyone who deploys or uses them is responsible for doing so |

## How it works

- **Verify, don't trust.** Each balance comes with a BLS threshold signature from the validator committee and a state proof. The wallet checks both on the device.
- **No ports, no VPN.** Nodes find each other on the BitTorrent Mainline DHT and connect over QUIC with hole punching.
- **No one runs the network alone.** The validator draw gives no single operator, the founder included, more than a third of the seats. Protocol upgrades need the validators' approval.

---

<sub>Built by Pipln. 한국어: 동해는 Mac이 직접 돌리고 직접 검증하는 블록체인입니다. 지금은 테스트넷이며, 테스트 코인에는 가치가 없습니다.</sub>
